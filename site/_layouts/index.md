<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">

  {%- include html-head.html -%}

  <body>

    {%- include body-header.html -%}

    <main class="page-content">
      <div class="wrapper">
        {{ content }}
      </div>
    </main>

    {%- include body-footer.html -%}

  </body>

</html>
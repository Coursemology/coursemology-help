<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">

  {% include head.html %}

  <body>

    {% include header.html %}

    <main class="container-fluid post-content" aria-label="Content">
      <div class="row">
        {% include sidebar.html %}

        <div class="post col-9">
          {{ content }}
        </div>
      </div>
      
    </main>

    {% include footer.html %}

  </body>

</html>

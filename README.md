Jika Web Reveal ini digunakan untuk hanya bekerja di homepage website

Cukup menambahkan;

    <b:if cond='data:blog.url  == data:blog.homepageUrl'>

    </b:if>
    
Dan dengan code diatas, Web Reveal ini hanya bekerja di homepage
dengan hasil code HTML;

    <b:if cond='data:blog.url  == data:blog.homepageUrl'>
    <div class='page-reveal'>
      <div class='element-3 element'/>
      <div class='element-1 element'/>
      <div class='element-2 element'/>
    </div>
    </b:if>

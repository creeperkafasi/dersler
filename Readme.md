# KTÜ Bilgisayar mühendisliği ders notları

***[Deniz Tunç](https://deniz.is-a.dev)***

Bölüm %30 İngilizce olduğundan notlar da Türkçe/İngilizce karışık bir şekilde. Kafama nasıl eserse öyle yazıyorum

Elinizde buraya eklemek istediğiniz not varsa ilgili dersin klasörüne [Markdown](https://www.markdownguide.org/getting-started/) formatında ekleyip Pull Request açabilir veya benimle herhangi bir şekilde iletişime geçebilirsiniz.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# 🌟 Welcome to My GitHub Pages Demo 🌟

This is a **test page** created to showcase the power and simplicity of GitHub Pages.

---

## 🌐 Navigation

- [About]({{ site.baseurl }}/about)
- [Contact]({{ site.baseurl }}/contact)

---

## ✨ Features

- 🖋️ **Markdown Support**: Easily format your content using markdown with intuitive syntax.
- 🔄 **Live Preview**: See changes instantly on your GitHub Pages site.
- 🎨 **Customizable Themes**: Choose from a variety of themes to make your site unique.

---

## 📰 Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

---

## 💻 Code Snippet Example

Here’s an example of a simple `Hello, World!` program in Python:

```python
def hello_world():
    print("Hello, World!")

hello_world()
```

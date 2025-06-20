[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Phantasm0009)](https://github.com/anuraghazra/github-readme-stats)
<!-- OSS Finder Widget - Markdown Version -->
## 🔍 Good First Issues

> **Powered by [OSS Finder](http://localhost:5173)**

**All Languages**
**Showing:** 3 recent issues

<!-- Widget will be injected here -->
<div id="oss-finder-widget-md"></div>

<script>
fetch('http://localhost:5000/api/widget/issues?limit=3&theme=light&style=card&showDescription=true&showStats=true&format=markdown')
  .then(response => response.text())
  .then(markdown => {
    document.getElementById('oss-finder-widget-md').innerHTML = markdown;
  });
</script>

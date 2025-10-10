Catering JR — Fix Kit

Upload everything in this folder to your repo ROOT (same level as index.html).

1) Files to upload/replace:
   - index.html
   - menu-gallery.html
   - sitemap.xml
   - .nojekyll  (empty file — prevents Jekyll from interfering)
   - images/ (entire folder with .webp)

2) After uploading:
   - Repo Settings -> Pages:
       Source: main / root
       Custom domain: cateringjr.com  (or www.cateringjr.com)
       Enforce HTTPS: ON

3) DNS checklist at your registrar:
   A  185.199.108.153
   A  185.199.109.153
   A  185.199.110.153
   A  185.199.111.153
   AAAA 2606:50c0:8000::153
   AAAA 2606:50c0:8001::153
   AAAA 2606:50c0:8002::153
   AAAA 2606:50c0:8003::153
   CNAME for www -> rodolfo09899.github.io

4) Test URLs:
   https://cateringjr.com/
   https://www.cateringjr.com/menu-gallery.html
   https://rodolfo09899.github.io/  (always works even before DNS completes)

If any image shows a broken icon, click its link and verify the target file exists.
Spaces in file names must be encoded: 'A B.png' -> 'A%20B.png'.

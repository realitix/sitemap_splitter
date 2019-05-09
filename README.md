# sitemap_splitter

Script to split large sitemap into several small sitemaps

With this script, you can easily split a large sitemap into several one and create a sitemap index.

To run this script:

- You must execute it in the folder with the `sitemap.xml` file: `python splitter.py`
- The original sitemap file is renamed `backup_sitemap.xml`
- The `sitemap.xml` file now contains the sitemap index
- You must set the prefix `BASE_URL` in the script head, the base url is used in the sitemap index.

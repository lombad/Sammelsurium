# Contribute

I provide an interactive bash script to automatically generate links in the correct format, which can be copy pasted to the `README.md`. It sits inside this repository and is called `linkgen`.

Via your `bash` terminal just run:

```
$ ./linkgen
Enter URL: https://google.com
Enter Title: Search Engine
Enter Description: Most popular search engine on the net       
Enter Tag[s] (A B C): SEARCH

- **Search Engine** - [https://google.com](https://google.com)

  Most popular search engine on the net

  ![SEARCH](https://img.shields.io/badge/-SEARCH-informational)

```

Otherwise contributers pls use the following template to add new links

```
- **Short Description** - [https://duckduckgo.com](https://duckduckgo.com)

  Long Description
  
  ![LABEL](https://img.shields.io/badge/-LABEL-<COLOR>)
```

# Issues

If links don not work, pls add it to an Issue.

# Pull Requests

If you have contributions open a pull request to inform me about your updates.

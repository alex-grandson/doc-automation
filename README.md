# YADRO tryout

This is sample CI/CD project as yadro tryout task

## Requirements

### Set up an elementary CI chain

- Create a public git repository
- Create a documentation page in the Sphinx format in this repository (http://www.sphinx-doc.org /) with brief information about yourself
- Configure the assembly of static html pages by commit to this repository using the public build service
- Set up automatic uploading of build results to a public site

### Recommendations for implementation:

- Use a public repository on GitHub (https://github.com)
- Use sphinx-quickstart
- Use GitHub Actions (https://docs.github.com/en/actions)
- Use GitHub Pages (https://pages.github.com)

## Run manually

```bash
docker compose up --build docs nginx
```

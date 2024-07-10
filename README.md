# demo-jinko-api-cookbook

A light demonstration of Jinko API feature based on a Jupyter Notebook. 

## Quick start

### Setup

1. Join [jinko.ai](https://www.jinko.ai), create or choose a project.
2. Register an "Editor" API token from the [project settings](https://doc.jinko.ai/docs/quick-start)
3. Copy `.envrc.sample` to `.envrc` then edit the values there:
   - `JINKO_API_KEY`: The API token you created before at step 2
   - `JINKO_PROJECT_ID`: You'll find it in the project url (a long UUID)
   - `JINKO_BASE_URL`: Keep the default value.
4. Source the environnement file with `source .envrc`  (we recommend the use of [direnv](https://direnv.net/))

### Run Jupyter Lab

This project rely on [poetry](https://python-poetry.org/) to manage dependency, but any other dependency manager may be used.

```sh
poetry install
poetry shell
poetry run jupyter-lab
```


## References

- [Jinko Homepage](https://www.jinko.ai) - Join Jinko, log in to your account.
- [Jinko API Documentation (alpha)](https://doc.jinko.ai) - API Reference, tutorials, cookbooks and format documentation.
- [Jinkommunity](https://community.jinko.ai/) - End-user documentation, knowledge base, release notes and resources.


---

<small>
[Nova In Silico](https://www.novainsilico.ai)
</small>

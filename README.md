# Ampsight's `graphene-django` fork

This is a fork of the `graphene-django` package, which is a part of the `graphene` project. This fork is intended to be used in the `cloud-vector-2-0-django` project.

This fork includes two changes:

1. The bundled version of GraphiQL includes the _Explorer_ plugin.
2. GraphiQL's NPM dependencies are bundled with the package, rather than being fetched via CDN. (This is essential for high side operation.)

The changes are implemented in the `v2.15.0-ampsight` branch of this repository.

See the `package.json` file in `graphene_django/static` for more information, including the list of NPM dependencies.

**NOTE:** The `package.json` file lists the dependencies that are used by the GraphiQL interface, but the production bundles of each have been extracted and included in the repository (under `static/js` and `static/css`). Some bundles have been renamed to avoid conflicts.

---

**The source repository can be found [here](https://github.com/graphql-python/graphene).**

**The docs can be found [here](https://docs.graphene-python.org/projects/django/en/latest/).**

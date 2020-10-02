# Nu HTML Validator on OpenShift

To run Nu HTML Validator on your OpenShift cluster, first create a new namespace, then apply the manifests in the `manifests` directory.

```
$ oc new-project validator
$ oc apply -f https://github.com/pittar/nu-html-validator/manifests -n validator 
```

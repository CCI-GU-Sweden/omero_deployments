To create deplpyment
> oc create deployment -f your-file.yaml

To update with new version of file
> oc apply -f your-new-file.yaml

Get help
> oc explain bla.ge.asdg.

Run an image in open shift
> oc run --image

Create deployment from image
> oc create deployment redis-omero-test --image=public.ecr.aws/bitnami/redis:8.2.2-debian-12-r0

dry run to yaml file
> oc create deployment redis-omero-test --image=public.ecr.aws/bitnami/redis:8.2.2-debian-12-r0 --dry-run -o yaml > redis-omero-test.yaml

Create service from pod
> oc expose 
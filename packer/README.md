# gcp/packer
Packer script for image baking on GCP

* V1 = Install packages from the packer file
* V2 = Install packages from provisioner.sh
* V3 = Install packages from provisioner.sh and uses the image_family to avoid mentioning image version.
* apache = Image baking with Apache Server (requires apache.json and prep_apache.sh file)
* glusterfs = Image baking with GlusterFS

Scripts uses a GCP service account and a JSON file with your account token.

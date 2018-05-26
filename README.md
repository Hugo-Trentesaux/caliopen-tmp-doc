# Install caliopen on vm

## Create virtual machine at gandi

- debian8
- manage sudoers (or do everything in root)
- install docker-ce https://docs.docker.com/install/linux/docker-ce/debian/#install-docker-ce-1
- install docker-compose https://docs.docker.com/install/linux/docker-ce/debian/#install-docker-ce-1
- install git and clone https://github.com/CaliOpen/Caliopen.git
- checkout on branch develop_hackathon
- go to the 'develop' doc http://caliopen.readthedocs.io/en/develop/install/frontend-development/
- (see troubleshooting) `sysctl -w vm.max_map_count=262144`
- do not build, but `docker-compose up -d redis cassandra elasticsearch`





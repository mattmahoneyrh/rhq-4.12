
This repository contains some RHQ-supporting bits around Docker, like a Dockerfile to get started with RHQ and so on.

Demo how RHQ Dockerfile works https://plus.google.com/u/0/events/clp274bhmdfvi4ol7csh2fd7n38?authkey=CPGuh8eZtrG5oAE

To build and run rhq docker container: 1. Install docker-io $ yum -y install docker-io 2. Build rhq image from Dockerfile $ ./build.sh 3. Start rhq image container $ ./run.sh

rhq should be accessible with http://:27080


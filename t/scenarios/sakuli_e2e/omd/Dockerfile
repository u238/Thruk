FROM  consol/omd-labs-centos:nightly

# uncomment to test against latest daily
#RUN rpm -Uvh "https://labs.consol.de/repo/testing/rhel7/i386/labs-consol-testing.rhel7.noarch.rpm"
#RUN yum -y makecache
#RUN yum -y install omd-labs-edition-daily
#RUN omd -f update demo

COPY playbook.yml /root/ansible_dropin/
COPY test.cfg /root/
COPY thruk_extra.conf /root/

openshift-showterm
========================

Showterm version running on OpenShift.

To get this app running on OpenShift, [sign up for OpenShift Online](https://www.openshift.com/app/account/new), [install the RHC command line tools](https://www.openshift.com/developers/rhc-client-tools-install), and run the following commands:

    rhc setup
    rhc app create showterm ruby-1.9 postgresql-9.2 --from-code=http://github.com/codemiller/openshift-showterm.git

For more information about Showterm, see http://www.showterm.io.


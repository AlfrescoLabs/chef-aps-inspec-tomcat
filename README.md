# chef-aps-inspec-tomcat Inspec Profile

Inspec profile for [chef-aps-appserver](https://github.com/Alfresco/chef-aps-appserver) cookbook

To use it in your Kitchen suite add:

```
verifier:
  inspec_tests:
    - name: chef-aps-inspec-tomcat
      git: https://github.com/Alfresco/chef-aps-inspec-tomcat
```

This Profile depends on [chef-alfresco-inspec-utils](https://github.com/Alfresco/chef-alfresco-inspec-utils) to import libraries and matchers
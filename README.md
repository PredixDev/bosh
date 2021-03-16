# Hello!

This repo is being used as a way to distribute what had traditionally been dev BOSH releases shuttled around from jumpbox to jumpbox.

Head over to the `Releases` tab to get the tarballs for:

 - kms-plugin

   ```
   releases:
   - name: kms-plugin
     sha1: ca73d883f65508cb159cfe79734a10ac48b8aa28
     url: https://github.com/PredixDev/bosh/releases/download/kms-plugin-1.0.0/kms-plugin-1.0.0.tgz
     version: 1.0.0
   ```
  
 - wazuh

   ```
   releases:
   - name: wazuh
     sha1: c1072279cd2ecbc2ea878d04e8e41d4c383af0b9
     url: https://github.com/PredixDev/bosh/releases/download/wazuh-3.11.4/wazuh-3.11.4.tgz
     version: 3.11.4
   ```
   
   ```
   releases:
   - name: wazuh
     sha1: 160230b47a0cbf8eed2bdde6a07618bce34401dd
     url: https://github.com/PredixDev/bosh/releases/download/wazuh-3.2.1.3/wazuh-3.2.1.3.tgz
     version: 3.2.1.3
   ```

 - os-conf

   ```
   releases:
   - name: os-conf
     sha1: 039320faf59dd320ebfb3046225882a307215648
     url: https://github.com/PredixDev/bosh/releases/download/os-conf-19/os-conf-19+dev.2.tgz 
     version: 19+dev.2
   ```


 - grootfs

   ```
   releases:
    - name: grootfs
      sha1: ac4a9f6f293504ce0d4f9b202ee549f8acf07c29
      version: 0.24.custom
      url: https://github.com/PredixDev/bosh/releases/download/grootfs-release-0.24.custom/grootfs-release-0.24.custom.tgz 
   ```



 - sudo
  
   Remember to add a `sleep 5` if colocated with `os-conf` pre-start script with any sudo commands in them

   ```
   releases:
   - name: sudo
     version: '1'
     sha1: 41b25be8619b98fce56feca0294381f31867f334
     url: https://github.com/PredixDev/bosh/releases/download/sudo-boshrelease-1/sudo-boshrelease.tar.gz 
   ```

   ```
   releases:
   - name: sudo
     version: '2'
     sha1: 203219d9b53f90a9e6057d470428190c400484f5
     url: https://github.com/PredixDev/bosh/releases/download/v2/sudo-boshrelease.2.tar.gz
   ```


> PaaS Team Rocks!

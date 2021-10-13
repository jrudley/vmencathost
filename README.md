# vmencathost
encryption at host vm sample


under microsoft.compute/virtualmachines add the following to enable encryption at host with a platform key
          "securityProfile": {
              "encryptionAtHost": true
          },

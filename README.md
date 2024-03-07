# automation
    
    automation
    ├── allure-ios-business   ----------->to generate testReport                    
    ├── allure-ios-consumer   ----------->to generate testReport  
    ├── app
    │   ├── android
    │   │   ├── business
    │   │   │   └── consumer.apk     --------------> upload the business android apk file for test
    │   │   └── consumer
    │   │       └── business.apk     --------------> upload the consumer android apk file for test
    │   └── ios
    │       ├── business
    │       │   └── business.ipa     --------------> upload the business ios ipa file for test
    │       └── consumer
    │           └── consumer.ipa     --------------> upload the consumer ios ipa file for test
    ├── automationServer
    │   └── index.js
    └── test
        ├── specsBusiness           ---------------> test script for consumer
        │   ├── android
        │   │   ├── function.js     ---------------> test case scenario 
        │   │   └── index.js        ---------------> main file to test scripts  here we import functions
        │   └── ios
        │       ├── function.js      
        │       └── index.js         
        └── specsConsumer           ---------------> test script for consumer
            ├── android    
            │   ├── function.js
            │   └── index.js         
            └── ios
                ├── function.js
                └── index.js        

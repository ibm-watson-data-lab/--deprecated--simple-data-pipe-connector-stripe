# Simple Data Pipe Connector for Stripe.com

##### [Simple Data Pipe](https://developer.ibm.com/clouddataservices/simple-data-pipe/) connector for [Stripe.com](http://www.stripe.com)

This repository contains the Stripe.com Simple Data Pipe connector. The connector should be used with latest version of the Simple Data Pipe implementing the [Simple Data Pipe SDK](https://github.com/ibm-cds-labs/simple-data-pipe-sdk).

### Pre-requisites

##### Install the Stripe.com connector

  Install the connector using [these instructions](https://github.com/ibm-cds-labs/simple-data-pipe/wiki/Installing-a-Simple-Data-Pipe-Connector) into the Simple Data Pipe.  

### Using the Stripe.com Connector 

To load billing information from stripe.com:
* Select __Stripe__ for the _Type_ when creating a new pipe.  
* In the _Connect_ page, enter the __OAuth consumer key__ and __consumer secret__ from the Stripe account settings page.
* Click __Connect to Stripe__.
* If prompted to authenticate, log in using your Stripe credentials.
* Grant the Simple Data Pipe read access to your data.
* In the _Pick tables_ page, select __All tables__ to load data for all supported stripe object types or a single object type (e.g. customer) to only load a subset of data.
* Schedule a pipe run or run the pipe immediately.

#### License 

Copyright [2015-2016] IBM Cloud Data Services

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.



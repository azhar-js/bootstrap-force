Twitter Bootstrap for Visualforce
=================

## Support for Visualforce
This flavor of Bootstrap has been modified to play nice (or at least nicer) with Visualforce by including a higher level of specificity to the CSS. If you have any questions or issues, post them in the issues or do a pull request if you add/fix/change anything that might be useful for others.

Currently, only `css/bootstrap.css` has undergone modifications.



## Getting Started

Clone the repo, `git clone git@github.com:colinloretz/visualforce-bootstrap.git`.


## Adding Bootstrap as a Static Resource
Create a zip archive of all the assets. In Salesforce, upload this zip file as a static resource. You can do so under **Setup > Develop > Static Resources**.



## Using Bootstrap in Visualforce
To include the assets in your visualforce page, please refer to [Delivering Static Resources with Visualforce](http://wiki.developerforce.com/page/Delivering_Static_Resources_with_Visualforce).

In order to make everything look neat, be sure to wrap all of your Bootstrap HTML markup in an div with an ID of `force`, as shown below.

	<div id = "force">
	 
	<!-- Bootstrap HTML markup here -->
	
	</div>
	

## Original Bootstrap Authors
Thank you for all your work on Bootstrap!

**Mark Otto**

+ http://twitter.com/mdo
+ http://github.com/markdotto

**Jacob Thornton**

+ http://twitter.com/fat
+ http://github.com/fat



Copyright and license
---------------------

Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

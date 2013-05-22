AFNetworking Modified
====
This isn't the [official AFNetworking repository](https://github.com/AFNetworking/AFNetworking). Check the original repo for more information.

<p align="center" >
  <img src="https://github.com/AFNetworking/AFNetworking/raw/gh-pages/afnetworking-logo.png" alt="AFNetworking Logo" title="AFNetworking">
</p>


Changes
----
* Remove seldom used class: AFPropertyListRequestOperation, AFXMLRequestOperation.
* Remove UIImageView category and AFImageRequestOperation. [SDWebImage](https://github.com/rs/SDWebImage) maybe a better choice.
* SystemConfiguration and MobileCoreServices framework aren't optional now. We always needs network reachability and MIME type detection.
* Some AFNetworking Extensions included: [AFHTTPRequestOperationLogger](https://github.com/AFNetworking/AFHTTPRequestOperationLogger)
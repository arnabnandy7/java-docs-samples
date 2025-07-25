# Google Cloud Platform Java Samples

![Kokoro Build Status](https://storage.googleapis.com/cloud-devrel-kokoro-resources/java/badges/java-docs-samples.png)
[![Coverage Status](https://codecov.io/gh/GoogleCloudPlatform/java-docs-samples/branch/master/graph/badge.svg)](https://codecov.io/gh/GoogleCloudPlatform/java-docs-samples)

<a href="https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/java-docs-samples&page=editor&open_in_editor=README.md">
<img alt="Open in Cloud Shell" src ="http://gstatic.com/cloudssh/images/open-btn.png"></a>

This repository holds sample code written in Java that demonstrates the
[Google Cloud Platform](https://cloud.google.com/docs/).

Some samples have accompanying guides on <cloud.google.com>. See respective
README files for details.

## Set Up

1. [Set up your Java Development Environment](https://cloud.google.com/java/docs/setup)

1. Clone this repository:

        git clone https://github.com/GoogleCloudPlatform/java-docs-samples.git

1. Obtain authentication credentials.

    Create local credentials by running the following command and following the
    oauth2 flow (read more about the command [here][auth_command]):

        gcloud auth application-default login

    Or manually set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable
    to point to a service account key JSON file path.

    Learn more at [Setting Up Authentication for Server to Server Production Applications](ADC).

    *Note:* Application Default Credentials is able to implicitly find the credentials as long as the application is running on Compute Engine, Kubernetes Engine, App Engine, or Cloud Functions.

## Contributing

* See the [Contributing Guide](CONTRIBUTING.md)

## Licensing

* See [LICENSE](LICENSE)

## Source Code Headers

Every file containing source code must include copyright and license
information. This includes any JS/CSS files that you might be serving out to
browsers. (This is to help well-intentioned people avoid accidental copying that
doesn't comply with the license.)

Apache header:

    Copyright 2020 Google LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[ADC]: https://developers.google.com/identity/protocols/application-default-credentials
[cred]: http://google.github.io/google-auth-library-java/releases/0.6.0/apidocs/com/google/auth/Credentials.html?is-external=true
[options]: http://googlecloudplatform.github.io/google-cloud-java/0.12.0/apidocs/com/google/cloud/ServiceOptions.Builder.html#setCredentials-com.google.auth.Credentials-
[auth_command]: https://cloud.google.com/sdk/gcloud/reference/beta/auth/application-default/login

## GitAds Sponsored
[![Sponsored by GitAds](https://gitads.dev/v1/ad-serve?source=arnabnandy7/java-docs-samples@github)](https://gitads.dev/v1/ad-track?source=arnabnandy7/java-docs-samples@github)



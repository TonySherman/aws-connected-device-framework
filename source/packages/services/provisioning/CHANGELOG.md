# Change Log - @cdf/provisioning

This log was last generated on Thu, 04 Aug 2022 18:39:36 GMT and should not be manually modified.

## 5.3.3
Thu, 04 Aug 2022 18:39:36 GMT

### Patches

- fix small typo in documentation

## 5.3.2
Thu, 21 Jul 2022 21:10:03 GMT

### Patches

- fixed a bug where certificate ARN was not passed for policy attachment

## 5.3.0
Fri, 15 Jul 2022 15:57:02 GMT

### Minor changes

- Added cross region support for ACMPCA

## 5.2.0
Thu, 30 Jun 2022 00:07:08 GMT

### Minor changes

-  updated ACM PCA integration to support registering certificates using CA's

## 5.1.1
Tue, 21 Jun 2022 00:47:55 GMT

### Patches

- update to node 16.x

## 5.1.0
Thu, 02 Jun 2022 00:45:32 GMT

### Minor changes

- Added support for creating and registering AWS IoT device certificates using AWS ACM PCA.
- add the option to provision thing and associate with certificate generated by AWS IoT

## 5.0.2
Mon, 21 Mar 2022 21:58:32 GMT

### Patches

- Upgrade dependencies marked as deprecated

## 5.0.1
Thu, 10 Mar 2022 00:08:34 GMT

### Patches

- Fixed misnamed configuration properties.

## 5.0.0
Thu, 17 Feb 2022 09:27:38 GMT

### Breaking changes

- migrate configuration to use dotenv-flow and deployment to use installer

## 4.2.5
Fri, 28 Jan 2022 02:31:34 GMT

### Patches

- Fixed misnamed configuration properties.

## 4.2.4
Tue, 25 Jan 2022 19:57:26 GMT

### Patches

- Fixes an error-level log message in request handler to correctly show a status code

## 4.2.3
Tue, 28 Dec 2021 18:37:09 GMT

### Patches

- Addressed github security dependabot alerts

## 4.2.2
Tue, 28 Sep 2021 22:04:37 GMT

### Patches

- Replaced references to CDF components being referred to as services to modules to avoid confusion with AWS services.
- properly handle not found errors in provisioning

## 4.2.1
Wed, 11 Aug 2021 01:26:49 GMT

### Patches

- opensource related minor changes

## 4.0.1
Wed, 21 Jul 2021 16:46:57 GMT

### Patches

- The generated lambda bundle size has been reduced.


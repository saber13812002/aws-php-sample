# AWS SDK for PHP Sample Project for Liara

A simple PHP application illustrating usage of the AWS SDK for PHP.

## Source

https://docs.min.io/docs/how-to-use-aws-sdk-for-php-with-minio-server.html


## Requirements

A `composer.json` file declaring the dependency on the AWS SDK is provided. To
install Composer and the SDK, run:

    curl -sS https://getcomposer.org/installer | php
    php composer.phar install

If you have windows

google how to install composer in windows


## Create Storage Server with Liara.ir CDN Services

goto https://liara.ir

create an account

enable your cdn service :

- copy endpoint 
- copy key 
- copy secret in the txt file 


Create bucket named : for example saber

upload file for example aa111.jpg and aa22.jpg

edit policy from left panel by click on ... on your bucket (saber)

prefix : aa 
permission read and write


## Basic Configuration

You need to set up your AWS security credentials before the sample code is able
to connect to AWS. 

open sample.php 

replace variables in file

## Running the S3 sample

run sample every where you want

you can see your image as binary.... ;)

you can see your downloaded picture beside your sample.php file

## License

This sample application is distributed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).


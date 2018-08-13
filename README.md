# ec2-price-check
Gives a quick price check for an instance type

## Dependencies
* curl

## Arguments
### help (-h|--help)
Prints help
```
price_check -h
```

### region (-r|--region)
Specifies region for which you would like the price\
Default: us-east-1
```
price_check -r us-west-1 r4.large
```

## Example
```
$ price_check t2.medium
```

## Installation
To install, simply add the `price_check` bash script to your PATH.
I personally like to do this via a `~/bin` directory, but you are free to do it however you wish.

Powered By: [https://github.com/Bjorn248/graphql_aws_pricing_api](https://github.com/Bjorn248/graphql_aws_pricing_api)

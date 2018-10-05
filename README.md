# Serverless F# Starter

A F# starter project for [Serverless Framework](https://serverless.com/framework/) with [AWS Extensions for .NET CLI](https://github.com/aws/aws-extensions-for-dotnet-cli).

### Requirements

- [Install .NET Core](https://www.microsoft.com/net/download)
- [Install the Serverless Framework](https://serverless.com/framework/docs/providers/aws/guide/installation/)
- [Configure your AWS CLI](https://serverless.com/framework/docs/providers/aws/guide/credentials/)

### Installation

Create a new project

```sh
$ serverless install --url https://github.com/fwang/serverless-fsharp-starter --name serverless-fsharp-starter
```


### Usage

Build

```sh
$ ./build.sh
```

Invoke a function locally

```
$ serverless invoke local -f hello
```

### Deploying

Deploy your project

```sh
$ serverless deploy
```

Deploy a single function

```sh
$ serverless deploy function --function hello
```

### Support

- Send us an [email](mailto:frank@seed.run) if you have any questions
- Open a [new issue](https://github.com/AnomalyInnovations/serverless-fsharp-starter/issues/new) if you've found a bug or have some suggestions.
- Or submit a pull request!

### Maintainers

Maintained by Frank Wang ([@fanjiewang](https://twitter.com/fanjiewang)) & Jay V ([@jayair](https://twitter.com/jayair)). [**Subscribe to our newsletter**](http://eepurl.com/cEaBlf) for updates. Send us an [email](mailto:contact@anoma.ly) if you have any questions.

<p align="center">
<img src="https://app.emailvalidation.io/img/logo/emailvalidation.png" width="300"/>
</p>

# emailvalidation-go: Golang Email Validation API

This package is a Golang wrapper for [emailvalidation.io](https://emailvalidation.io) that aims to make the usage of the API as easy as possible in your project. 
emailvalidation.io is a simply and easy-to-use email validation & verification API that provides useful information about any email address.

## Usage

Initialize the API with your API Key (get one for free at [emailvalidation.io](https://emailvalidation.io)):

```go
emailivalidation.Init("YOUR-API-KEY")
```

Afterwards you can make calls to the API like this:

### Status Endpoint

```go
emailivalidation.Status()
```

### Info Endpoint

```go
emailivalidation.Info({
    "email": "john@doe.com",
    "catch_all": 1
})
```


Find out more about our endpoints, parameters and response data structure in the [docs](https://emailvalidation.io)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[docs]: https://emailivalidation.io/docs
[emailvalidation.io]: https://emailivalidation.io


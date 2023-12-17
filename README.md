# Elastiseach 8.11 php client for composer 1

========================

Check documentation for more details at [https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/index.html](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/index.html)

## Contents

- [Installation](#installation)
- [Connecting](#connecting)
- [Usage](#usage)

***

## Installation

Add to composer.json:

```json
{
    "repositories": [
      {
            "type": "package",
            "package": {
                "name": "focus3d/elasticsearch-composer1",
                "version": "dev-main",
                "source": {
                    "type": "git",
                    "url": "https://github.com/Focus3D/elasticsearch-composer1.git",
                    "reference": "main"
                }
            }
        }
    ],
    "require": {
        "focus3d/elasticsearch-composer1": "dev-main"
    }
}
```

## Connecting

Refer to the [Connecting section](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_connecting)
of the getting started documentation.

## Usage

The `elasticsearch-php` client offers 400+ endpoints for interacting with 
Elasticsearch. A list of all these endpoints is available in the 
[official documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html)
of Elasticsearch APIs.

Here we reported the basic operation that you can perform with the client: 
index, search and delete.

* [Creating an index](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_creating_an_index)
* [Indexing a document](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_indexing_documents)
* [Getting documents](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_getting_documents)
* [Searching documents](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_searching_documents)
* [Updating documents](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_updating_documents)
* [Deleting documents](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_deleting_documents)
* [Deleting an index](https://www.elastic.co/guide/en/elasticsearch/client/php-api/current/getting-started-php.html#_deleting_an_index)

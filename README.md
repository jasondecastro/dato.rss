# DATO.RSS
*The best RSS Search Engine experience you can find.*


DATO.RSS - Search Engine: Quickly search through the millions of available RSS feeds.

DATO.RSS - API: Turns feed data into an awesome API. The API simplifies how you handle RSS, Atom, or JSON feeds. You can add and keep track of your favourite feed data with a simple, fast and clean REST API. All entries are enriched by Machine Learning and Semantic engines.

## Live

https://datorss.com

## Example

``` bash

curl 'https://datorss.com/api/searches?q=news' | json_pp

{
  "data": [
    {
      "id": "86b0f829-e300-4eef-82e1-82f34d03aff6",
      "type": "entry",
      "attributes": {
        "title": "\"Pandemic, Infodemic\": 2 Cartoon Characters Battling Fake News In Assam",
        "url": "https://www.ndtv.com/india-news/coronavirus-pandemic-infodemic-2-cartoon-characters-battling-fake-news-in-assam-2222333",
        "published_at": 1588448805,
        "body": "An English daily in Assam's Guwahati has been publishing a cartoon strip to tackle the fake news related to the coronavirus pandemic. The two central characters- \"Pandemic and Infodemic\"- are being...<img src=\"http://feeds.feedburner.com/~r/NDTV-LatestNews/~4/lEmH201Q8jI\" height=\"1\" width=\"1\" alt=\"\"/>",
        "text": "An English daily in Assam's Guwahati has been publishing a cartoon strip to tackle the fake news related to the coronavirus pandemic. The two central characters- \"Pandemic and Infodemic\"- are being...",
        "categories": [
          "all india"
        ],
        "sentiment": null,
        "parent": {
          "id": "c97bdae6-b5d1-4966-b9f3-615e29d4d47d",
          "title": "NDTV News  -  Special",
          "url": "feed:http://feeds.feedburner.com/NDTV-LatestNews",
          "rank": 99
        },
        "tags": []
      },
      "relationships": {
        "feed": {
          "data": {
            "id": "c97bdae6-b5d1-4966-b9f3-615e29d4d47d",
            "type": "feed"
          }
        }
      }
    },
  ]
}

```
## Wiki

All documentation is in the Wiki section. Feel free to make it better, of course.

https://github.com/davidesantangelo/dato.rss/wiki

## Built With

- [Ruby on Rails](https://github.com/rails/rails) &mdash; Our back end API is a Rails app. It responds to requests RESTfully in JSON.
- [PostgreSQL](https://www.postgresql.org/) &mdash; Our main data store is in Postgres.
- [Redis](https://redis.io/) &mdash; We use Redis as a cache and for transient data.
- [Feedjira](https://github.com/feedjira/feedjira) &mdash; Feedjira is a Ruby library designed to parse feeds.
- [Dandelion](https://dandelion.eu) &mdash; Semantic Text Analytics as a service.
- [Sidekiq](http://sidekiq.org) &mdash; Simple, efficient background processing for Ruby.
- [JSON:API Serialization](https://github.com/jsonapi-serializer/jsonapi-serializer) &mdash; A fast JSON:API serializer for Ruby Objects..
- [PgSearch](https://github.com/Casecommons/pg_search) &mdash; PgSearch builds named scopes that take advantage of PostgreSQL's full text search..

Plus *lots* of Ruby Gems, a complete list of which is at [/main/Gemfile](https://github.com/davidesantangelo/dato.rss/blob/main/Gemfile).

## Buy me a coffee

If you want to support me in server costs to keep dato.ess free and up, consider sponsorize! Thanks!

<a href="https://github.com/sponsors/davidesantangelo" target="_blank">GitHub sponsor</a>


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/davidesantangelo/dato.rss. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
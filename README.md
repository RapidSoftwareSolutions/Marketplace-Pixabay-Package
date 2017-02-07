[![](https://scdn.rapidapi.com/RapidAPI_banner.png)](https://rapidapi.com/package/Pixabay/functions?utm_source=RapidAPIGitHub_PixabayFunctions&utm_medium=button&utm_content=RapidAPI_GitHub)

# Pixabay Package
Get license-free stock images, vectors and illustrations.
* Domain: pixabay.com
* Credentials: apiKey

## How to get credentials: 
0. [Login](https://pixabay.com/en/accounts/login/?next=/en/accounts/logout/) into your Pixabay account. 
1. Go to [docs page](https://pixabay.com/api/docs/) and find `key` parameter.

## Pixabay.searchImages
Search images.

| Field         | Type       | Description
|---------------|------------|----------
| apiKey        | credentials| Your Pixabay API key.
| query         | String     | A URL encoded search term. If omitted, all images are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang          | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id            | String     | ID, hash ID, or a comma separated list of values for retrieving specific images. In a comma separated list, IDs and hash IDs cannot be used together.
| highResolution| Boolean    | Choose between retrieving high resolution images and image details. When selecting details, you can access images up to a dimension of 960 x 720 px.
| orientation   | String     | Whether an image is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category      | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth      | String     | Minimum image width. Default: `0`
| minHeight     | String     | Minimum image height. Default: `0`
| editorsChoice | String     | Select images that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch    | String     | A flag indicating that only images suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order         | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page          | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage       | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`

## Pixabay.searchPhotos
Search photos.

| Field         | Type       | Description
|---------------|------------|----------
| apiKey        | credentials| Your Pixabay API key.
| query         | String     | A URL encoded search term. If omitted, all photos are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang          | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id            | String     | ID, hash ID, or a comma separated list of values for retrieving specific images. In a comma separated list, IDs and hash IDs cannot be used together.
| highResolution| Boolean    | Choose between retrieving high resolution images and image details. When selecting details, you can access images up to a dimension of 960 x 720 px. 
| orientation   | String     | Whether an image is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category      | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth      | String     | Minimum image width. Default: `0`
| minHeight     | String     | Minimum image height. Default: `0`
| editorsChoice | String     | Select photos that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch    | String     | A flag indicating that only photos suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order         | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page          | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage       | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`

## Pixabay.searchIllustrations
Search Illustrations.

| Field         | Type       | Description
|---------------|------------|----------
| apiKey        | credentials| Your Pixabay API key.
| query         | String     | A URL encoded search term. If omitted, all illustrations are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang          | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id            | String     | ID, hash ID, or a comma separated list of values for retrieving specific images. In a comma separated list, IDs and hash IDs cannot be used together.
| highResolution| Boolean    | Choose between retrieving high resolution images and image details. When selecting details, you can access images up to a dimension of 960 x 720 px. 
| orientation   | String     | Whether an image is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category      | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth      | String     | Minimum image width. Default: `0`
| minHeight     | String     | Minimum image height. Default: `0`
| editorsChoice | String     | Select illustrations that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch    | String     | A flag indicating that only illustrations suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order         | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page          | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage       | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`

## Pixabay.searchVectorImages
Search vector images.

| Field         | Type       | Description
|---------------|------------|----------
| apiKey        | credentials| Your Pixabay API key.
| query         | String     | A URL encoded search term. If omitted, all images are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang          | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id            | String     | ID, hash ID, or a comma separated list of values for retrieving specific images. In a comma separated list, IDs and hash IDs cannot be used together.
| highResolution| Boolean    | Choose between retrieving high resolution images and image details. When selecting details, you can access images up to a dimension of 960 x 720 px. 
| orientation   | String     | Whether an image is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category      | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth      | String     | Minimum image width. Default: `0`
| minHeight     | String     | Minimum image height. Default: `0`
| editorsChoice | String     | Select images that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch    | String     | A flag indicating that only images suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order         | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page          | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage       | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`

## Pixabay.searchVideos
Search videos.

| Field        | Type       | Description
|--------------|------------|----------
| apiKey       | credentials| Your Pixabay API key.
| query        | String     | A URL encoded search term. If omitted, all videos are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang         | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id           | String     | ID or a comma separated list of values for retrieving specific videos.
| orientation  | String     | Whether an video is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category     | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth     | String     | Minimum video width. Default: `0`
| minHeight    | String     | Minimum video height. Default: `0`
| editorsChoice| String     | Select videos that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch   | String     | A flag indicating that only videos suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order        | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page         | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage      | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`

## Pixabay.searchAnimations
Search animation.

| Field        | Type       | Description
|--------------|------------|----------
| apiKey       | credentials| Your Pixabay API key.
| query        | String     | A URL encoded search term. If omitted, all videos are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang         | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id           | String     | ID or a comma separated list of values for retrieving specific videos.
| orientation  | String     | Whether an video is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category     | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth     | String     | Minimum video width. Default: `0`
| minHeight    | String     | Minimum video height. Default: `0`
| editorsChoice| String     | Select videos that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch   | String     | A flag indicating that only videos suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order        | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page         | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage      | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`

## Pixabay.searchFilms
Search films.

| Field        | Type       | Description
|--------------|------------|----------
| apiKey       | credentials| Your Pixabay API key.
| query        | String     | A URL encoded search term. If omitted, all videos are returned. This value may not exceed 100 characters. Example: `yellow+flower`
| lang         | String     | Language code of the language to be searched in. Accepted values: `cs, da, de, en, es, fr, id, it, hu, nl, no, pl, pt, ro, sk, fi, sv, tr, vi, th, bg, ru, el, ja, ko, zh`. Default: `en`
| id           | String     | ID or a comma separated list of values for retrieving specific videos.
| orientation  | String     | Whether an video is wider than it is tall, or taller than it is wide. Accepted values: `all`, `horizontal`, `vertical`. Default: `all`
| category     | String     | Accepted values: `fashion`, `nature`, `backgrounds`, `science`, `education`, `people`, `feelings`, `religion`, `health`, `places`, `animals`, `industry`, `food`, `computer`, `sports`, `transportation`, `travel`, `buildings`, `business`, `music`
| minWidth     | String     | Minimum video width. Default: `0`
| minHeight    | String     | Minimum video height. Default: `0`
| editorsChoice| String     | Select videos that have received an Editor's Choice award. Accepted values: `true`, `false`. Default: `false`
| safesearch   | String     | A flag indicating that only videos suitable for all ages should be returned. Accepted values: `true`, `false`. Default: `false`
| order        | String     | How the results should be ordered. Accepted values: `popular`, `latest`. Default: `popular`
| page         | String     | Returned search results are paginated. Use this parameter to select the page number. Default: `1`
| perPage      | String     | Determine the number of results per page. Accepted values: `3 - 200`. Default: `20`


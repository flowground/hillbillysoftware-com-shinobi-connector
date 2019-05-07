# ![LOGO](logo.png) shinobiapi **flow**ground Connector

## Description

A generated **flow**ground connector for the shinobiapi API (version v1).

Generated from: https://api.apis.guru/v2/specs/hillbillysoftware.com/shinobi/v1/swagger.json<br/>
Generated at: 2019-05-07T17:42:20+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### Returns data on queried actor/actress. Result set limited to 5 records

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `accesstoken` - _required_
* `Query` - _required_

### Add new actor or actress to database

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

### Add new show to database

*Tags:* `Television (Shows, Episodes, & Statuses)`

### Get known aliases for Movies or Television shows from passed imdbID

*Tags:* `Aliases (Movie & Television Show Aliases)`

#### Input Parameters
* `AccessToken` - _required_
* `imdbID` - _required_

### Get known aliases for Movies or Television shows

*Tags:* `Aliases (Movie & Television Show Aliases)`

#### Input Parameters
* `AccessToken` - _required_
* `Title` - _required_ - Title of movie or television show

### Gets all awards by nominiee

*Tags:* `Awards (Television & Movies)`

#### Input Parameters
* `AccessToken` - _required_
* `Nominee` - _required_

### Gets all awards for requested year

*Tags:* `Awards (Television & Movies)`

#### Input Parameters
* `Year` - _required_

### Gets TV Schedule for selected data

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_
* `Date` - _required_ - date format year-month-day
* `Country` - _required_ - US / CA / NL / BE / DE / GB or FR

### Returns list of available countries in calendar database

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_

### Gets a list of available networks

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_

### Returns list of seasons available in the calendar for show

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_

### Get Calendar by showname and season

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_
* `Season` - _required_

### Will return show schedule for queried showname and year

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_
* `Year` - _required_

### Will return show schedule for today for all countries in database

*Tags:* `Calendar (Television Show Schedules)`

#### Input Parameters
* `AccessToken` - _required_

### Returns all shows queried actor/actress is or has been in

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `Actor` - _required_ - Part of, or full name of actor

### Returns list of show actor is appearing in

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `Actor` - _required_ - Full name of actor

### Returns all actors in queried tvshow

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `accesstoken` - _required_
* `ShowName` - _required_

### Get crew list by ID

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `ID` - _required_ - IMDBID, TVmazeID, or TVDBID

### Gets list of productions searched person is/was involved in.

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `PersonName` - _required_

### Get crew list by showname

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `ShowName` - _required_ - Full exact showname

### Returns crew for queried show.

*Tags:* `Cast & Crew (Cast & Crew in Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `Phrase` - _required_ - Part of, or full showname to search for

### Gets all episodes for selected ID

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `ID` - _required_ - imdbID

### Gets list of episodes for specified imdbID and Season number

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `ID` - _required_ - imdbID
* `Season` - _required_ - Season number

### Gets all episodes for selected show

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `Showname` - _required_

### Gets latest season number based on show name

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_

### Returns last available season number in database, based on passed imdbID

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `ID` - _required_ - imdbID

### Returns number of available seasons and episodes

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `ID` - _required_ - imdbID

### Gets list of avaiable IMDB ids from Movies and TV Show databases, you can use those to query other end points that need ID's

*Tags:* `Miscellaneous (Conversion & other Utilities)`

#### Input Parameters
* `AccessToken` - _required_
* `Query` - _required_

### Get images available for movie/tv show with passed imdbID

*Tags:* `Images (Movie & Television Show Images)`

#### Input Parameters
* `AccessToken` - _required_
* `imdbID` - _required_

### Get images available for movie/tv show with passed query

*Tags:* `Images (Movie & Television Show Images)`

#### Input Parameters
* `Accesstoken` - _required_
* `Query` - _required_ - Name or part of name from Movie or Show
* `Strictmatch` - _optional_

### Gets available magnet hashes on passed date (yyyy-mm-dd).  Feature not available on free plan, please donate to be able to use this feature.

*Tags:* `Magnets (Magnet hashes of Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `Date` - _required_

### Returns list of magnet hashes for passed IMDBID.  Feature not available on free plan, please donate to be able to use this feature.

*Tags:* `Magnets (Magnet hashes of Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `imdbID` - _required_ - ID with or without tt prefix

### Try and find magnet links for queried movie.  Feature not available on free plan, please donate to be able to use this feature

*Tags:* `Magnets (Magnet hashes of Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `Query` - _required_ - Name or part of name of movie or tv show

### Returns results based on query, Feature not available on free plan, please donate to be able to use this feature.

*Tags:* `Magnets (Magnet hashes of Movies & Television Shows)`

#### Input Parameters
* `AccessToken` - _required_
* `TVShow` - _required_

### MovieID_Get

*Tags:* `Movies (Movies, Documentaries, & made for Television Movies)`

#### Input Parameters
* `accesstoken` - _required_
* `imdbID` - _required_

### Searches for movies, result set limited to 5 records

*Tags:* `Movies (Movies, Documentaries, & made for Television Movies)`

#### Input Parameters
* `AccessToken` - _required_
* `Query` - _required_

### Returns Albumart for passed AlbumID

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `AlbumID` - _required_

### Gets CD art for passed MusicBrainzID

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `MBID` - _required_ - MusicBrainzID

### Get Artist / Band information on MusicBrainzID

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `MBID` - _required_ - MusicBrainzID

### Get albums from passed ArtistID

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `ArtistID` - _required_ - ID of artist or band to retrieve albums from

### Retrieves artist / band Banner and logo based on ArtistID

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `ArtistID` - _required_ - ArtistID of artist or band

### Retrieves artist / band Banner and logo based on artist or bandname

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_ - Name of artist or band

### Provides extended information, which includes all known albums and music videos of artist / band

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_

### Get information about passed band name or artist

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_ - Name (or part) of band or artist name

### Returns all lyrics for requested AlbumID

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `AlbumID` - _required_

### Get lyrics for band or artist (record set limited to 25)

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_ - Name (or partial) of band or artist (record set limited to 25)

### Get lyrics on song title

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `Song` - _required_ - Name or part of song name

### Get all tracks from requested album

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `AlbumID` - _required_ - AlbumID (can be retrieved via album endpoint)

### Lists all videos available for this Artist / Band

*Tags:* `Music (Artists ,Bands, Tracks, AlbumArt, CoverArt, & Videos)`

#### Input Parameters
* `AccessToken` - _required_
* `ArtistID` - _required_

### Returns ratings from various resources(IMDB,Rotten Tomatoes, metaCritics, TVMaze etc) of passed IMDBid

*Tags:* `Ratings  (Movie & Television Show Ratings)`

#### Input Parameters
* `AccessToken` - _required_
* `imdbID` - _required_

### RatingByName_Get

*Tags:* `Ratings  (Movie & Television Show Ratings)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_

### Returns status of queried show (query can be IMDB, TVDB, or showname)

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `Query` - _required_ - Query can be IMDB, TVDB, or Show name

### Returns TVShow information based on IMDBid

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `accesstoken` - _required_
* `id` - _required_ - imdbID of show you want info on
* `imdbID` - _required_

### Returns results based on query, result set limited to 5 records

*Tags:* `Television (Shows, Episodes, & Statuses)`

#### Input Parameters
* `AccessToken` - _required_
* `Query` - _required_

### Get Trailers for passed imdbID

*Tags:* `Trailers (Movie & Television Show Trailers)`

#### Input Parameters
* `AccessToken` - _required_
* `imdbID` - _required_

### Get trailer count for passed ID

*Tags:* `Trailers (Movie & Television Show Trailers)`

#### Input Parameters
* `AccessToken` - _required_
* `imdbID` - _required_

### Get trailer count for passed name (Movie title or TVShow name)

*Tags:* `Trailers (Movie & Television Show Trailers)`

#### Input Parameters
* `AccessToken` - _required_
* `Name` - _required_

### Gets trailers by search phrase (limited to 10 records)

*Tags:* `Trailers (Movie & Television Show Trailers)`

#### Input Parameters
* `AccessToken` - _required_
* `Phrase` - _required_ - Trailer you like to search for

## License

**flow**ground :- Telekom iPaaS / hillbillysoftware-com-shinobi-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

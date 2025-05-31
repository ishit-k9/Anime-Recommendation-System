# Anime-Recommendation-System
This repository is created and maintained by Ishit Gehlot and contains the colab notebook of Anime Recommendation system.  In this notebook I've made a Content-Based Anime Recommendation System. 

---

#***ANIME RECOMMENDATION SYSTEM***

---


* ***FRAMING THE PROBLEM***

I've a dataset of 28666 animes and I've to build an Anime Recommendation System and deploy it on website.

* ***GATHERING DATA***

I've fetched data from Jikan API, which is an unofficial API of MyAnimelist.


* ***TECHNIQUE USED***

I am going to use Content-Based filtering, in which recommendation is decided on the basis of content they like.

* ***EVALUATION METRICS***

PASS

* ***ASSUMPTIONS***

Since the data is missing 90% english titles, we're assuming that people will know the japanese name of animes.

* ***DATA DESCRIPTION***

This dataset specially target to those people who want to improve their skill of data cleaning. Also this can be used for NLP.

Data Description:-
mal_id: Unique MyAnimeList identifier.

url: Direct link to the anime’s MAL page.

images: Dictionary with URLs for poster, cover, etc.

trailer: YouTube trailer URL (if available).

approved: Boolean indicating MAL moderation approval.

titles: All titles (English, Japanese, synonyms).

title: Primary title (default language).

title_english: Official English title.

title_japanese: Official Japanese title.

title_synonyms: Alternate titles (aliases).

type: Media type (TV, Movie, OVA, etc.).

source: Original material (Manga, Light Novel, etc.).

episodes: Total episode count.

status: Airing status (Finished, Ongoing, etc.).

airing: Boolean for currently airing.

aired: Date range (start/end of broadcast).

duration: Episode runtime (e.g., "24 min").

rating: Age rating (PG-13, R, etc.).

score: Average user rating (1-10).

scored_by: Number of users who rated it.

rank: MAL popularity ranking.

popularity: Position in most-viewed list.

members: Number of MAL users with it in their list.

favorites: Number of users who favorited it.

synopsis: Plot summary.

background: Production/release context.

season: Airing season (Winter, Summer, etc.).

year: Release year.

broadcast: Weekly airing schedule (e.g., "Sundays").

producers: Production companies involved.

licensors: Licensed-by companies (for distribution).

studios: Animation studios.

genres: Main genres (Action, Romance, etc.).

explicit_genres: Adult-oriented genres (Hentai, etc.).

themes: Sub-genres/themes (e.g., "Music", "Military").

demographics: Target audience (Shonen, Shojo, etc.).


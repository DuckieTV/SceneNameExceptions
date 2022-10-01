# DuckieTV SceneNameExceptions

Maps TRAKT_ID's to Scene Names.

credits to Sickbeard's exception list: https://raw.github.com/midgetspy/sb_tvdb_scene_exceptions/gh-pages/exceptions.txt

filters applied:
- Removed `(([12][09][0-9]{2}))` (all years between 19* and 20* within () )
- Replaced `\'` with `'`
- Replaced surrounding `'` with `"`
- Replaced `.` with ` ` 
- Remove special characters `(){}[]/\|:;<>!@#$%^&*-=_+`
- line sort
------------------
## List directory:
- TraktSceneDateExceptions.json contains trakt_id of series on the scene that use a date scheme instead of the usual SxxExx.    
- SceneDateExceptions.json same as above but with tvdb_id as used by older Dtv Nightly up to version 202101312304 (Jan 31st 2021).    
- TraktSceneNameExceptions.json contains trakt_id of series that use a different title to that provided by Trakt.tv.    
- SceneNameExceptions.json same as above but with tvdb_id as used by older Dtv Nightly up to version 202101312304 (Jan 31st 2021).    
- TraktidTvdbidXref.json contains manually curated Trakt_id vs tvdb_id, via a manual thetvdb lookup for those Trakt.tv series records that are missing tvdb_ids. These are mostly Foreign Language series (from NLD, DEU, CHN, KOR, JPN, TUR, RUS, IND, ESP, etc), or series that TVDB considers a continuation of the original root series but are loaded on TMDB as separate series.      

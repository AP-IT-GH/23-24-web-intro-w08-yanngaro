# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel.
4. Voer het verzoek uit en bekijk de respons.
{
    "status": "ok",
    "totalResults": 1000,
    "articles": [
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Merkur.de",
            "title": "Mysteriöser Fund auf dem Mars – Nasa spricht von „Reifenspuren“ oder „Drachenschuppen“ - Merkur.de",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiiAFodHRwczovL3d3dy5tZXJrdXIuZGUvd2lzc2VuL211c3Rlci1yZWlmZW5zcHVyZW4tZHJhY2hlbnNjaHVwcGVuLW1hcnMtZnVuZC1uYXNhLXJvdmVyLWN1cmlvc2l0eS1teXN0ZXJpb2VzLXNlbHRzYW1lci1zdGVpbi05MzAyMTc2Ny5odG1s0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T20:37:03Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "MSN",
            "title": "MSN - MSN",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMikgFodHRwczovL3d3dy5tc24uY29tL2VuLWdiL25ld3Mvd29ybGQvdm9sY2Fuby1zcGV3cy01ay1nb2xkLWR1c3QtY3J5c3RhbHMtZXZlcnktZGF5LXdoaWNoLWxhbmQtNjAwLW1pbGVzLWF3YXkvYXItQUExbnAxOFY_b2NpZD13ZWF0aGVyLXZlcnRocC1mZWVkc9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T20:25:16Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "TODAY",
            "title": "NASA graduates new astronauts for Orion capsule mission - TODAY",
            "description": null,
            "url": "https://news.google.com/rss/articles/CCAiC0hpREdvMkNTVjFVmAEB?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T20:00:04Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Capitalist",
            "title": "Por que nos beijamos? Descubra as surpreendentes razões científicas por trás de um beijo - Capitalist",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiXWh0dHBzOi8vY2FwaXRhbGlzdC5jb20uYnIvamEtc2UtcGVyZ3VudG91LXBvci1xdWUtbm9zLWJlaWphbW9zLWEtY2llbmNpYS1yZXZlbGEtYXMtcmVzcG9zdGFzL9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T19:34:37Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Midi Libre",
            "title": "Des étoiles filantes plein les yeux : comment observer les Lyrides, dont le pic d'activité est prévu ce dimanche ? - Midi Libre",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMinQFodHRwczovL3d3dy5taWRpbGlicmUuZnIvMjAyNC8wNC8yMS9kZXMtZXRvaWxlcy1maWxhbnRlcy1wbGVpbi1sZXMteWV1eC1jb21tZW50LW9ic2VydmVyLWxlcy1seXJpZGVzLWRvbnQtbGUtcGljLWRhY3Rpdml0ZS1lc3QtcHJldnUtY2UtZGltYW5jaGUtMTE5MDQ2MDMucGhw0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T19:31:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "infobae",
            "title": "La telemedicina que usarán los astronautas en la Luna y Marte, se prueba en la Antártida argentina - infobae",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMikwFodHRwczovL3d3dy5pbmZvYmFlLmNvbS9zYWx1ZC9jaWVuY2lhLzIwMjQvMDQvMjEvbGEtdGVsZW1lZGljaW5hLXF1ZS11c2FyYW4tbG9zLWFzdHJvbmF1dGFzLWVuLWxhLWx1bmEteS1tYXJ0ZS1zZS1wcnVlYmEtZW4tbGEtYW50YXJ0aWRhLWFyZ2VudGluYS_SAacBaHR0cHM6Ly93d3cuaW5mb2JhZS5jb20vc2FsdWQvY2llbmNpYS8yMDI0LzA0LzIxL2xhLXRlbGVtZWRpY2luYS1xdWUtdXNhcmFuLWxvcy1hc3Ryb25hdXRhcy1lbi1sYS1sdW5hLXktbWFydGUtc2UtcHJ1ZWJhLWVuLWxhLWFudGFydGlkYS1hcmdlbnRpbmEvP291dHB1dFR5cGU9YW1wLXR5cGU?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T19:15:08Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Diario de Avisos",
            "title": "Los científicos descubren un planeta que puede ser incluso más habitable que la Tierra | Canariasenred - Noticias de Canarias - Diario de Avisos",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiigFodHRwczovL2RpYXJpb2RlYXZpc29zLmVsZXNwYW5vbC5jb20vY2FuYXJpYXNlbnJlZC9sb3MtY2llbnRpZmljb3MtZGVzY3VicmVuLXVuLXBsYW5ldGEtcXVlLXB1ZWRlLXNlci1pbmNsdXNvLW1hcy1oYWJpdGFibGUtcXVlLWxhLXRpZXJyYS_SAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T18:32:53Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Garhwalpost.in"
            },
            "author": "Garhwal Post",
            "title": "Alien Planets on Earth – 2 - Garhwal Post",
            "description": null,
            "url": "https://garhwalpost.in/alien-planets-on-earth-2/",
            "urlToImage": "https://garhwalpost.in/wp-content/uploads/2024/04/11.Getting-ready-to-go-into-the-polar-ice-crevice-scaled.jpg",
            "publishedAt": "2024-04-21T18:15:46Z",
            "content": "All Around the World with the Most Travelled Indian\r\nBy Nitin Gairola\r\nThere is a reason why I use the term Most Travelled Indian of the Natural World. This is to make it clear that, first and foremo… [+7511 chars]"
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "20 minutes",
            "title": "Un saut depuis la stratosphère et une chute libre à 300 km/h - 20 minutes",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMibWh0dHBzOi8vd3d3LjIwbWluLmNoL2ZyL3ZpZGVvL3BvbGUtbm9yZC11bi1zYXV0LWRlcHVpcy1sYS1zdHJhdG9zcGhlcmUtZXQtdW5lLWNodXRlLWxpYnJlLWEtMzAwLWttaC0xMDMwODk5OTjSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T18:03:41Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Okdiario",
            "title": "El hallazgo científico que lo cambia todo: el descubrimiento que confirma lo que todos nos temíamos - Okdiario",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMihwFodHRwczovL29rZGlhcmlvLmNvbS9jdXJpb3NpZGFkZXMvaGFsbGF6Z28tY2llbnRpZmljby1xdWUtbG8tY2FtYmlhLXRvZG8tZGVzY3VicmltaWVudG8tcXVlLWNvbmZpcm1hLWxvLXF1ZS10b2Rvcy1ub3MtdGVtaWFtb3MtMTI3MTYyNDLSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T18:00:31Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "iefimerida",
            "title": "Πώς θα είναι η Σελήνη το 2100 -Τα υπόγεια σπίτια, το σιδηροδρομικό δίκτυο, τα ρομπότ και οι κάθετοι κήποι - iefimerida",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiN2h0dHBzOi8vd3d3LmllZmltZXJpZGEuZ3Ivem9pL3NlbGluaS1wb3MtdGhhLWVpbmFpLTIxMDDSATtodHRwczovL3d3dy5pZWZpbWVyaWRhLmdyL3pvaS9zZWxpbmktcG9zLXRoYS1laW5haS0yMTAwP2FtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:49:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "صحيفة الشرق الأوسط",
            "title": "وفقا لعلم النفس... 5 أحلام شائعة ومعانيها - صحيفة الشرق الأوسط",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi9QFodHRwczovL2Fhd3NhdC5jb20vJUQ4JUI1JUQ4JUFEJUQ4JUFBJUQ5JTgzLzQ5Nzc4NDYtJUQ5JTg4JUQ5JTgxJUQ5JTgyJUQ4JUE3LSVEOSU4NCVEOCVCOSVEOSU4NCVEOSU4NS0lRDglQTclRDklODQlRDklODYlRDklODElRDglQjMtNS0lRDglQTMlRDglQUQlRDklODQlRDglQTclRDklODUtJUQ4JUI0JUQ4JUE3JUQ4JUE2JUQ4JUI5JUQ4JUE5LSVEOSU4OCVEOSU4NSVEOCVCOSVEOCVBNyVEOSU4NiVEOSU4QSVEOSU4NyVEOCVBN9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:38:23Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Yahoo News Canada",
            "title": "The Lyrids are here: How and when to see the meteor shower peak in 2024 - Yahoo News Canada",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiRmh0dHBzOi8vY2EubmV3cy55YWhvby5jb20vbHlyaWRzLXNlZS1tZXRlb3Itc2hvd2VyLXBlYWstMDQwMTE3NzQ0Lmh0bWzSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:37:30Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "La 100",
            "title": "Científicos anunciaron que la Tierra podría partirse en dos y alertaron a la población: dónde se daría el quiebre - La 100",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMimwFodHRwczovL2xhMTAwLmNpZW5yYWRpb3MuY29tL2N1cmlvc2lkYWRlcy9jaWVudGlmaWNvcy1hbnVuY2lhcm9uLXF1ZS1sYS10aWVycmEtcG9kcmlhLXBhcnRpcnNlLWVuLWRvcy15LWFsZXJ0YXJvbi1hLWxhLXBvYmxhY2lvbi1kb25kZS1zZS1kYXJpYS1lbC1xdWllYnJlL9IBqgFodHRwczovL2xhMTAwLmNpZW5yYWRpb3MuY29tL2N1cmlvc2lkYWRlcy9jaWVudGlmaWNvcy1hbnVuY2lhcm9uLXF1ZS1sYS10aWVycmEtcG9kcmlhLXBhcnRpcnNlLWVuLWRvcy15LWFsZXJ0YXJvbi1hLWxhLXBvYmxhY2lvbi1kb25kZS1zZS1kYXJpYS1lbC1xdWllYnJlLz9vdXRwdXRUeXBlPWFtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:34:59Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Interesting Engineering"
            },
            "author": "Amal Jos Chacko",
            "title": "NASA seeks help to save stranded Mars samples; SpaceX among frontrunners - Interesting Engineering",
            "description": "NASA seeks private companies' innovative ideas to rescue Mars Sample Return mission amid rising costs and delays.",
            "url": "https://interestingengineering.com/science/nasa-mars-sample-retrieval",
            "urlToImage": "https://cms.interestingengineering.com/wp-content/uploads/2024/04/Artwork-showing-human-skeletal-muscles-front-view-17.png",
            "publishedAt": "2024-04-21T17:32:00Z",
            "content": "Starship has the potential to return serious tonnage from Mars within ~5 years\r\n— Elon Musk (@elonmusk) April 15, 2024\r\nFor scientists, getting their hands on a cache of Mars samples after three deca… [+979 chars]"
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Libération",
            "title": "Désextinction des espèces : «Je n'ose pas imaginer ce que ça donnerait si on voulait faire revenir des lions des cavernes en Suisse» - Libération",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi2QFodHRwczovL3d3dy5saWJlcmF0aW9uLmZyL2Vudmlyb25uZW1lbnQvYmlvZGl2ZXJzaXRlL2Rlc2V4dGluY3Rpb24tZGVzLWVzcGVjZXMtamUtbm9zZS1wYXMtaW1hZ2luZXItY2UtcXVlLWNhLWRvbm5lcmFpdC1zaS1vbi12b3VsYWl0LWZhaXJlLXJldmVuaXItZGVzLWxpb25zLWRlcy1jYXZlcm5lcy1lbi1zdWlzc2UtMjAyNDA0MjBfR0FJTEVJRVIyQkhQSkI0S0dPV1A2NkJLTkkv0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:26:11Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Phys.Org"
            },
            "author": "Christian Schroeder",
            "title": "Crucial building blocks of life on Earth can more easily form in outer space, says new research - Phys.org",
            "description": "The origin of life on Earth is still enigmatic, but we are slowly unraveling the steps involved and the necessary ingredients. Scientists believe life arose in a primordial soup of organic chemicals and biomolecules on the early Earth, eventually leading to a…",
            "url": "https://phys.org/news/2024-04-crucial-blocks-life-earth-easily.html",
            "urlToImage": "https://scx2.b-cdn.net/gfx/news/hires/2024/crucial-building-block.jpg",
            "publishedAt": "2024-04-21T17:20:01Z",
            "content": "This article has been reviewed according to Science X's \r\neditorial process\r\nand policies.\r\nEditors have highlighted\r\nthe following attributes while ensuring the content's credibility:\r\nfact-checked\r… [+5236 chars]"
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Respectmag",
            "title": "L'économie invisible : ces habitudes quotidiennes qui grèvent votre budget sans que vous en ayez conscience - Respectmag",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMihQFodHRwczovL3d3dy5yZXNwZWN0bWFnLmNvbS9sLWVjb25vbWllLWludmlzaWJsZS1jZXMtaGFiaXR1ZGVzLXF1b3RpZGllbm5lcy1xdWktZ3JldmVudC12b3RyZS1idWRnZXQtc2Fucy1xdWUtdm91cy1lbi1heWV6LWNvbnNjaWVuY2Uv0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:20:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "fr.de",
            "title": "Neue Beweise für Existenz des mysteriösen „Planet 9“: „Spricht stark für seine Anwesenheit“ - fr.de",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMigAFodHRwczovL3d3dy5mci5kZS93aXNzZW4vc3RhcmstYW53ZXNlbmhlaXQtZXhpc3Rlbnotd2VsdGFsbC1teXN0ZXJpb2VzZXItcGxhbmV0LTktbmV1bi1uZXVlLWJld2Vpc2Utc3R1ZGllLXNwcmljaHQtOTMwMjA3OTMuaHRtbNIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:16:10Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "DNA India"
            },
            "author": "Shivam Verma",
            "title": "6 stunning images taken from spacecrafts shared by NASA - DNA India",
            "description": "Check out 6 stunning images taken from spacecrafts shared by NASA",
            "url": "https://www.dnaindia.com/web-stories/viral/6-stunning-images-taken-from-spacecrafts-shared-by-nasa-1713715613792",
            "urlToImage": null,
            "publishedAt": "2024-04-21T17:15:23Z",
            "content": "Apr 21, 2024, 10:45 PM IST"
        }
    ]
}
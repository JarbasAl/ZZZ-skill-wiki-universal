## Universal Wikipedia
Search for Wikipedia articles

## Description 
Query [Wikipedia](https://www.wikipedia.org) for answers to all your questions!  Get just the
summary, or ask for more to get in-depth information.

uses english wikipedia, translates input and output to configured language

## Examples 
* "Tell me about Elon Musk"
* "Tell me about beans"
* "Check wikipedia for beans"
* "Search for water"

## logs


    23:04:04.383 - SKILLS - DEBUG - {"type": "recognizer_loop:utterance", "data": {"utterances": ["fala me sobre elon musk"]}, "context": null}
    23:04:04.497 - SKILLS - DEBUG - {"type": "4423900893043600903:Wiki", "data": {"confidence": 0.375, "EECDJAAIJDAEDGAAJADWikipedia": "fala me sobre", "target": null, "intent_type": "4423900893043600903:Wiki", "__tags__": [{"end_token": 2, "start_token": 0, "from_context": false, "entities": [{"confidence": 1.0, "data": [["fala me sobre", "EECDJAAIJDAEDGAAJADWikipedia"]], "key": "fala me sobre", "match": "fala me sobre"}], "key": "fala me sobre", "match": "fala me sobre"}, {"end_token": 4, "start_token": 3, "confidence": 0.5, "from_context": false, "entities": [{"confidence": 0.5, "data": [["elon musk", "EECDJAAIJDAEDGAAJADArticleTitle"]], "key": "elon musk", "match": "elon musk"}], "key": "elon musk", "match": "elon musk"}], "utterance": "fala me sobre elon musk", "EECDJAAIJDAEDGAAJADArticleTitle": "elon musk"}, "context": {"target": null}}
    23:04:04.505 - SKILLS - DEBUG - {"type": "mycroft.skill.handler.start", "data": {"name": "universal_intent_handler"}, "context": null}
    23:04:07.448 - mycroft_jarbas_utils.skills.auto_translatable:universal_intent_handler:56 - INFO - WikipediaSkill.handle_wiki_intent
    23:04:08.361 - SKILLS - DEBUG - {"type": "speak", "data": {"expect_response": false, "utterance": "espera um bocado enquanto procuro elon musk", "metadata": null}, "context": {"target_lang": "pt", "auto_translated": true, "target": null, "source_lang": "es"}}
    23:04:08.368 - SKILLS - DEBUG - {"type": "add_context", "data": {"word": "Elon Musk", "context": "EECDJAAIJDAEDGAAJADwiki_article"}, "context": null}
    23:04:08.375 - SKILLS - DEBUG - {"type": "add_context", "data": {"word": "1", "context": "EECDJAAIJDAEDGAAJADspoken_lines"}, "context": null}
    23:04:09.286 - SKILLS - DEBUG - {"type": "speak", "data": {"expect_response": false, "utterance": "Elon Reeve Musk e um magnate, investidor e engenheiro americano canadense de origem sul-africana.", "metadata": null}, "context": {"target_lang": "pt", "auto_translated": true, "target": null, "source_lang": "en"}}
    23:04:09.290 - SKILLS - DEBUG - {"type": "mycroft.skill.handler.complete", "data": {"name": "universal_intent_handler"}, "context": null}

## Credits 
Mycroft AI

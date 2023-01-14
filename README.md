# borgnetzwerk
The superproject over all submodules in the BorgNetzWerk.

# Execution order
a) Run one step for every item, then go to the next step, or
b) Run every step for one item, then go to the next item

## Information extraction

#### IDEAS
Read text from screen
Process images

### extract_from_html
To extract knowledge from Youtube and Spotify.
Can be used to feed into:

### pytube_bot
Download meta-data, infos and captions for videos.
Can do audio as well to be fed into:
Requirement: None
Optional: extract_from_html

### whisper
To upcycle the audios from pytube_bot to written text.
Requirement: pytube_bot

## information enhancement

### spellcheck
Requirement: whisper or pytube_bot

### NLP

#### Knowledge extraction

#### Lexikon

#### Lemmakon

#### Lemma per episode

#### Keywords

### Similarity

#### Lemma-vector

#### Topic-vector

## publishing

### obsidize

### wikify

### texify
# wordcloud-example
Exemplar program for creating wordcloud.To understand better, refer to this [video](https://www.youtube.com/watch?v=95p3cVkqYHQ).

## What is a wordcloud?

An image composed of words used in a particular text or subject, in which the size of each word indicates its frequency or importance.

## Installation

Install [wordcloud](https://github.com/amueller/word_cloud) using a simple pip command.

```
pip install wordcloud
```

**wikipedia** library is used for extracting wikipedia articles on any given topic. Install it using this pip command:
```
pip install wikipedia
```
## Usage

Run python script as:

```
python mywc.py <query>
```

For example:

```
python mywc.py india
```

will create wordcloud for the topic 'india' which looks like this:

![](https://raw.githubusercontent.com/nikhilkumarsingh/wordcloud-example/master/wc.png)

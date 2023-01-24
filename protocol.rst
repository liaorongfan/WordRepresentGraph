PROJECT PROTOCOL
========

Terms
-----

Label:
    The "Task" label is to mark in what cases a word is most used, here are 4 types and they are reading,
    writing, speaking and listening.

    The "Topic" label suggests on what topics or scenarios a word is normally used.


Collocation:
    A collocation is a general term referring to words that usually or always go together. 
    A collocation can perform various functions in a sentence (i.e. act as different parts of speech). 
    Some examples are “bunch of flowers” or “commit a crime.”

    => 词组搭配

    This fild is designed for writing

Phrase/Phrasal verb:
    A phrasal verb is usually a combination of a verb + a preposition which usually changes the meaning from
    that of the original verb. For example, “put + up with” means to tolerate, while “put + up” means to return
    something to its original/proper position (especially when cleaning),
    and “put + off” means to delay doing something until a later time.

    => 短语 / 动词短语

Chunk:
    a phrase or group of words which can be learnt as a unit by sb who is learning a language. Examples of
    chunks are ‘Can I have the bill, please?’ and ‘Pleased to meet you’

    => 话语组成部分

    In this project, "idioms" are treated as chunks for less word attributes used when coding

    This fild is designed for oral speaking English, It would be better to read its contents
    form time to time




Tokens
------

**EMPTY LINE**
    Visually, there is no content in a line,
    when coding "\\n" just after a header or title indicator "---" means EMPTY

** - **
    used in the beginning of each line to separate different items

** => **
    Translation indicator, used at interpreting English into Chinese,

** --> **
    paraphrasing indicator, used when describing or explaining an object in
    another way

** [ . ]: **
    Project key word indicator, used to mark key features of a word

    For example:

    [task] and [syn] will specify task type and synonym words respectively

    Note that the ":" follows the "]" is indispensable for argument parse
    when coding

** < ... > **
    Sentence indicator, used to lead and include a sentence. So as to allocate one
    sentence in multi-lines.

    For example:

    < During the excavation of ancient Babylon, evidence was found that
    soapmaking was known as early as 2800 BC. >

    If a sentence is just a short one, it'll be no need to use the indicator for
    convenience.

** R / W / S / L **
    used as [task] label for a word, where R means Reading, W denotes Writing, S indicates Speaking
    and L represents Listening


Key words
---------

[syn]

[relate]

[pronounce]

[task]

[topic]

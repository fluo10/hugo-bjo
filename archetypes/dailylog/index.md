+++
title = "{{ time.Format "Mon Jan 2 2006" .Date }}"
date =  {{ .Date }}
type = "log"
categories = [ "dailylog", ]
tags = [
    "",
]
[conditions]
weather = ""

[conditions.temparatures]
max = 0
min = 0

[timestamp]
wakeup = {{ .Date }}
gotobed = {{ .Date }}
+++

## Life

## Work

## Interests
# Accessibility-Screen-readers-Tests
This repo is dedicated to the different CSS and HTML properties test on the
different screen readers and their behaviour.

>> Currently all the tests are tested on Mac OS + Safari Browser + Voice Over screen reader.

## What is Screen Reader
Screen Reader is one of the assistive technolgoy used by the sighted users. There are many screen readers which are used healvily by the users. 

However, screen readers are dependent on the OS and browser combination highly.

## How to use Screen Reader?
Getting use of screen reader is not easy. As developer, one needs to spend good time to 
learn how to use screen reader and its behaviour.

## Popular Screen Reader

- Voice Over
- JAWS
- NVDA
- Talk Back

## Screen Reader, OS, and browser combination

  | Screen Reader | Mozilla | Chrome | Edge | Safari |
  | ------ | ------ | ------ | ------ | ------ | 
  | **Win + Voice Over** | NA | NA | NA | NA | NA |
  | **Win + NVDA** |  NA | NA | NA | NA | NA |
  | **Win + JAWS** | NA | NA | NA | NA | NA |
  | **Win + TalkBack** | NA | NA | NA | NA | NA |
  | **Mac + Voice Over** | NA | NA | NA | NA | YES |
  | **Mac + NVDA** |  NA | NA | NA | NA | NA |
  | **Mac + JAWS** | NA | NA | NA | NA | NA |

## Results
 | HTML/CSS Properties | Win + Voice Over | Win + NVDA | Win + JAWS | Win + TalkBack | Mac + Voice Over | Mac + NVDA |  Mac + JAWS |
 | ------ | ------ |  ------ | ------ | ------ | ------ | ------ | ------ |
 | **line-through** | NA | NA | NA | NA | Screen Reader will not identify line-through | NA | NA |
 | **font-weight** |  NA | NA | NA | NA | Screen Reader will not identify line-through | NA | NA |
 | **sub/sup** | NA | NA | NA | NA | Screen Reader will not identify line-through | NA | NA |
 | **display** | NA | NA | NA | NA | NA | NA | NA |
 | **float** | NA | NA | NA | NA | NA | NA | NA |
 | **flex** |  NA | NA | NA | NA | NA | NA | NA |
 | **position** | NA | NA | NA | NA | NA | NA | NA |
 | **font-size** | NA | NA | NA | NA | Screen Reader will still read the content of font-size:0  | NA | NA |
 | **Counter** | NA | NA | NA | NA | NA | NA | NA | NA |
 | **Currency** | NA | NA | NA | NA | NA | N | NA | NA |
 | **list-style** | NA | NA | NA | NA | Screen Reader will identify the OL and UL. For list-item roman it won't read as 1,2,3 but say 'i,i-i,i-i-i  | NA | NA |
 | **Nested list** | NA | NA | NA | NA | Screen Reader will not identify the nested list | NA | NA |

## Open for contribution
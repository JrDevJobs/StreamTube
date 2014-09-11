# <a href='http://www.jrdevjobs.com' target='_blank'>Jr.DevJobs</a> Challenge: Stream Tube

## Introduction
In this challenge you will create a webpage using YouTube's <a href='https://developers.google.com/youtube/v3/' target='_blank'>Data API</a> and <a href='https://developers.google.com/youtube/iframe_api_reference' target='_blank'>Player API</a> to search and endlessly stream YouTube videos.

You are free to do this in any language or framework, however the sample is written in JavaScript.

## Getting Started
To begin, Fork this repository to your GitHub account by clicking the Fork icon in the upper-right section of this page.

![Forking Image](https://s3-us-west-2.amazonaws.com/jrdevsimages/repos/fork_button.jpg)

*If you're new to Forking, we suggest reading the <a href='https://help.github.com/articles/fork-a-repo' target='_blank'>GitHub documentation</a> before moving forward.*

Finally, in order to use the YouTube APIs you must obtain a free API Key by <a href='https://developers.google.com/youtube/registering_an_application' target='_blank'>registering your project</a> with Google.

## <a name='userstory'></a>User Story
As a user, I want to search for YouTube videos, have them load and automatically play in an endless stream.

#### Details

* Take search input from the user and query YouTube for videos related to the search string
* Load the first video and automatically play it
* When a video ends, automatically load and play the next video
* Allow users to skip to the next and previous videos

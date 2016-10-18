go-reddit
=========

[![Build Status](https://travis-ci.org/cameronstanley/go-reddit.svg?branch=master)](https://travis-ci.org/cameronstanley/go-reddit)
[![GoDoc](https://godoc.org/github.com/cameronstanley/go-reddit?status.svg)](https://godoc.org/github.com/cameronstanley/go-reddit)
[![Go Report Card](https://goreportcard.com/badge/github.com/cameronstanley/go-reddit)](https://goreportcard.com/report/github.com/cameronstanley/go-reddit)

A Golang wrapper for the [Reddit API](https://github.com/reddit/reddit/wiki/API). This package aims to implement every endpoint exposed according to the [documentation](https://www.reddit.com/dev/api) in a user friendly, well tested and documented manner.

## Installation

Install the package with

`go get github.com/cameronstanley/go-reddit`

## Examples

````Go
// Returns a new client for invoking the API
client := reddit.Client{}

// Retrives a listing of default subreddits
client.GetDefaultSubreddits()

// Retrives a listing of hot articles for the "news" subreddit
client.GetHotArticles("news")
```

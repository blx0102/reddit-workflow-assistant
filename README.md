# Reddit Workflow Assistant

This is a small private-use tool I am building to help me review Reddit discussions more carefully before I participate.

The first version is read-only and human-in-the-loop. It is meant to help me understand public threads, check subreddit rules, and keep my own notes or draft replies before I decide whether to comment manually.

## Current scope

The app may use the Reddit API to read:

- public posts
- public comments
- search results
- subreddit rules

It will only be used with a small list of communities that I choose manually.

## What the app does

The app will help me:

- find discussions that may be relevant to topics I know about
- review the context of a thread before replying
- check subreddit rules before I participate
- keep private notes and possible draft replies

An LLM may be used to summarize threads or help draft possible replies, but all decisions and final posting are manual.

## What the app will not do

The app will not:

- post or comment automatically
- vote on posts or comments
- send private messages or chats
- follow users
- create accounts
- mass-post similar replies
- bypass API limits
- train AI models on Reddit data
- sell, license, or redistribute Reddit data

## Data handling

The app is intended to store only limited public thread metadata and my own notes or drafts. It is not designed to collect private data or build profiles about Reddit users.

If Reddit content is deleted, I intend to remove locally stored copies related to that content where applicable.

## Why not Devvit

Devvit seems best for apps that live inside Reddit communities, like community tools, interactive posts, games, or moderation tools.

This project is different. It is a private off-Reddit workflow for reviewing public discussions, keeping notes, and preparing drafts before I manually participate as a Reddit user. I do not need a Reddit-hosted UI or an app installed into a community.

## Status

Early prototype. Read-only access only.

# wawa fertility chat app

To setup, just run `./bin/setup`, then `./bin/rails server`, then hit `localhost:3000`.

This application uses only postgres.

A basic chat app using the latest version of Rails.

Requirements:
* Users should be able to sign up and be authenticated
* Users should have a display name
* Users should be able to join and leave chat rooms
* Chat rooms can have many users at a time
* Users can send message to chat rooms
* Messages should be real time
* Messages should contain text
* Messages should be persisted in a database

Technology to focus on:
* ActiveRecord
    * Migrations
    * Queries
* Hotwire
    * Turbo Frames
    * Turbo Streams
    * Stimulus
* Unit and integration testing

# Music Recommendation System using Spotify API and Python

Hey there! If you're looking to dive into the world of music recommendation systems, you've come to the right place. In this project, we're going to leverage the power of the Spotify API along with Python to create a system that offers personalized music recommendations tailored just for you.

## Let's Get Started

### Step 1: Set Up Your Spotify Account

First things first, you'll need a Spotify account. If you don't have one yet, no worries! Just head over to Spotify's website and sign up for free. Once you've got your account sorted, log in.

### Step 2: Navigate to Your Spotify Developer Dashboard

Now, it's time to access your Spotify Developer Dashboard. This is where the magic happens. Click on [here](https://developer.spotify.com/dashboard/) to land directly on the dashboard. If this is your first time here, make sure to sign the agreement and verify your email. Once done, we can proceed to the next step.

### Step 3: Create Your App

Exciting stuff! Click on the option to create a new app. Fill in the necessary details for your app description. After that, you'll be directed to your client ID and client secret. Keep these credentials safe, as we'll need them for building our Music Recommendation System.

## How to Use

To kickstart our Music Recommendation System, we'll utilize Python along with the Spotify API. But first, we need to obtain an access token to authenticate our requests to the Spotify API. Here's how you can get it:

## Required Libraries

Before diving into the code, make sure you have the following dependencies installed:

- Spotipy
- Pandas
- NumPy
- Scikit-learn

## Generating Awesome Recommendations

We're going to employ two main approaches for generating music recommendations: content-based filtering and popularity-based filtering.

### Content-Based Filtering

This method recommends music based on the similarity of their audio features. Using Spotipy, we'll fetch music data from Spotify and calculate similarity scores based on these features.

### Popularity-Based Filtering

Here, we recommend music based on their popularity scores. We'll even throw in a twist by weighting recent releases more heavily.

### Hybrid Approach

The hybrid approach combines the best of both worlds, merging content-based and popularity-based recommendations to provide you with the ultimate personalized experience.

## Putting It to the Test

To see the system in action, simply provide an input song name. The system will then generate recommendations based on this input, using our hybrid approach.

## Wrapping Up

Building a Music Recommendation System using the Spotify API and Python opens up a world of endless possibilities for discovering new music that resonates with your unique tastes and preferences. Let's dive in and start exploring!

PS: Inspired by Aman Kharwal's insightful project ideas, this Music Recommendation System using the Spotify API and Python aims to further explore the realm of personalized music discovery. You can check out Aman's original post [here](https://thecleverprogrammer.com/2023/07/31/music-recommendation-system-using-python/) for more inspiration and detailed insights! 

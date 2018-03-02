# YouTube-API-Project
______

## Data Systems - CS 181
### Ron Washington III & Z Elmandouh

## Provenance
> For this project, we are using the YouTube Data API and are using OAuth2 in order to access the data of an authenticated user. The purpose of this project is to enable a YouTube account to gather its own personal data and or data from YouTube and produce JSON files of authentication tokens. The given tokens will then be used within a later Jupyter Notebook to enable data collection. From there, authenticated users will be able to gather and manipulate YouTube data.

> Within the OAuth2 process, we are creating a project from a Google account with an associated YouTube account as the resource owner account. A .py file is needed for this project which will include neccessary identificaiton such as the client_id, scope, redirect, and etc. This file will contain JSON information which will be used to protect the account's private information.

______


## Notebook 1 - _Token acquisition notebook_
> Token acquisition notebook: this notebook handles the code cells/steps needed to get an access token. For the most part, these steps only need be executed one time, to go from first registration of a client with a provider to the point where an access token is received (nominally Step 8 of the OAuth Dance). If tokens need to be refreshed, then the cell(s) needed to refresh a token could be here as well.

## Notebook 2 - _Data acquisition notebook_
> Data acquisition notebook: this notebook starts from the premise of a valid token and takes the reader through the set of interactions acquiring and organizing the data from the provider. The notebook should detect and handle errors from the server, including, but not limited to, handling an expired token.

## Notebook 3 - _Visualization notebook_
> Results presentation notebook: this notebook documents, for a non-expert audience, the results of the data exploration, with the same standard of narrative and data presentation clarity as previous projects. Basically, presenting the capabilities of the project after data acquisition. Within this file the photo files contained within this repository correspond with each question.

______

## Limitations / Issues
> The current structure of this program only allows for one use to be authenticated at a time. Therefore, the data that will be gathered will only be relative to that one account. It would be advised in future usage of this program to enable it to enable multiple authentications to gather larger data sets. Based on the multiple data sets, there investigators could compare the statistics of videos within each account and trending.

> Another issue regarding this program is that it requires users to follow the format of input for authenticating a user. Meaning that the account being used is limited to Google - gmail. Thus, outside accounts would not be enabled. Additionally, there is not a documentation on extra syntax that could be used to gather more statistics; however, this information can be found on Google's YouTube API website.


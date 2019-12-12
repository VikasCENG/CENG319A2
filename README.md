# SearchView

## Table of Contents

1. Introduction
2. History
3. Major Methods/Attributes
4. Example Project Code
5. References

## Introduction 

SearchView is a Android widget, that is capable of providing tools to search for a given context in a Android Studio mobile application environment. The widget provides a user interface equipped with a search bar, that allows users to query a particular selection or search for available results. The main purpose of this tool being to use a search provider to check for available result, if existing part of the service, or code. The results of the query can be based on internal code that is fixed into the searchbar. This means, the widget automatically detects what the user wants to search for, by entering a letter or context specific to the desired selection. The search provider provides a list generated with all the available data at a specific time, and displays this data for the user to select, or view further details  on. There can also be instances, where a a user searches for a topic and is presented with valid suggestions to choose from,depending on what exists in the data interface.  SearchView is widely used with creating mobile applications, that require to search the internet to retrieve information on specific topics. This can be done through a delegated server, such as Firebase. The data can be stored into the database, and once the user enters a specific data type, the search provider would either provide valid results/suggestions available in a listed format part of the database/or vice-versa.In using this widget, the most common use occurs with the Actionbar. The searchbar sits on top of the ActionBar asthe interface to take in all the input, and either find the right match or provide similar suggestions for the user experience. SearchView filters the results by data thatt is available through browsing for specifc content, or data that exists as part of a online database somewhere on the internet. The search provider acts as the basis of providing the results, and reccomendations of what the user might want to query on next. For example,the widget provides ways to expand the experience by adding advanced features such as voice recognition. This can allow users to interact with their device and the search provider to gather results through verbal conversation,etc. 

## History

SearchView was introduced in API 11 of the Android system. The package library it mainly consisted of was the AppCompatActivity library, with backwards configuration back to Android 2.1. 

## Major Methods/Attributes

The major methods that are needed to use this widget are the following: 
- public boolean onQueryTextSubmit(String query)
- public boolean onQueryTextChange(String text)

So, onQueryTextSubmit is used to search a query based on waht the usertypes into the searchbar at the time of the submission. While, onQueryTextChaneg provides real-time updates of the user selections as they are typed into the searchbar layout. It basically searches the query, and automatically changes context if the user types a new letter, and as they enter new desired results, the searchview changes to the expected results from the query.

## Example Project Code

## References


Day 1.

You run a social media website called DoomSpace, where people of all ages can gather to admire DOOMSLAYER(The dog not the video game character) but your users can be quite unruly. Many of your users keep posting content that contains profanity, such as the word "fuck", "shit", etc...


Your task is to automatically filter a string to fix its profanity. For example lets take the post string of

    ```
        "OMGOMGOMG DOOMSLAYER is so fucking adorable I could LITERALLY SHIT MYSELF"
    ``` 

this would be changed to
    
    ```  
        "OMGOMGOMG DOOMSLAYER is so f**king adorable I could LITERALLLY S**T Myself"
    ```

In order to help you, DoomSpace's HR team has included a list of words that need to be fixed here is the data for that.
    
    ```
        fuck,
        shit,
        douche,
        piss,
        damn,
        wtf,
        hell,
        barbra streisand,
    ```

You are tasked with writing a function that will input an uncensored post, and output a censored post
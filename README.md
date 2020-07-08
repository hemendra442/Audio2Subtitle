# Audio2Subtitle
#Motto :-
Create video subtitles with translation(one language to another language) using Python MoviePy

#Example: I want to see subtitles in Telugu/any language, where audio is in English of a Youtube video.

#Steps:-
1. Extract audio from the video.
Using moviepy,video.audio for extracting audio.

2. Convert audio to text.
Using speech_recognition, converted and saved in to a text file.

3. Translate text into any preferred langugage.
Using google translator, i converted text from one language to another language.

4. show translated text on video.
Using moviepy.tools.SubtitlesClip shown telugu/any langugae on video.

Note:
As of now moviepy.tools.SubtitlesClip not supporting  other than English. 

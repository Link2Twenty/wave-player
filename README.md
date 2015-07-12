# <wave-player>

![ScreenShot](http://media.giphy.com/media/3oEduUPRhku9FpetlS/giphy.gif)

## Attributes

| Attribute Name | Functionality | Default |
|----------------|-------------|-------------|
| wavecolor | Color of the wave | #ffffff |
| progresscolor | Color of the portion of the wave already player | #CFD8DC |
| src* | location of the audio file |  |
| lean | which side do you want the button on | left |
| name | Name of audio to be displayed |  |
| title | Specific title, to be displayed smaller |  |
| coverart | location of cover art | art.jpg |
required*

## How to use

If you are looking at useing other peoples custom polymer elements I am going to guess you have some idea what's going on already. If not have a look at the [polymer site](http://polymer-project.org).

Put a link to wave player in your header, it should look something like.
```html
<link rel="import" href="bower_components/wave-player/wave-player.html">
```


Now that you have imported it you can get to using it on your page
```html
<wave-player 
		wavecolor="#e44d26" 
		progresscolor="#f16529" 
		src="mirror.mp3" 
		lean="left"
		name="Really long string, it's too long for one line!"
		title="Chapter 1 - the boy who lived"
		/>
```

## Special thanks
- Wave form visualizer - [wavesurfer.js](http://www.wavesurfer.fm/)
- Prateek Jadhwani - [prateekjadhwani](https://github.com/prateekjadhwani)

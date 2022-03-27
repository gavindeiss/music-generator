# music-generator

## Unzipping files

Before you can do anything, 2 of the files are too large to commit to git without compressing unfortunately. So you'll have to unzip them, do whatever work you need to do (tweaking hyperparams & generating songs), and then recompress before committing again. The two files are 

- .../music-generator/jazz_music/tmp/notesequences.tfrecord.zip
- .../music-generator/jazz_music/tmp/polyphony_rnn/sequence_examples/training_poly_tracks.tfrecord.zip

## Generating Songs

Our custom model has already been trained. So after unzipping the relevant files, to create a new song using you just need to...

1. cd to jazz-music in terminal
2. follow any relevant steps here (skip to the "Generating polyphonic tracks with your model" subheading): https://www.twilio.com/blog/training-a-neural-network-on-midi-music-data-with-magenta-and-python
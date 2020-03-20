# YogaAI
YogaAI is a responsive virtual yoga instructor that uses pose estimation to guide and correct a yogi.

# Dependencies
You'll need have the following installed:

* python3
* tensorflow 1.11 - pip wheel for 3.5 w/tflite working thanks to PINTO0309
* opencv3
* sci-kit learn

# Hardware
* raspberry pi 3+
* webcam
* speaker with aux
* monitor
* one way mirror + framing materials

# Install
` 1. git clone https://www.github.com/roshancode/YogaAI `
` 2. cd YogaAI `
` 3. ./install.sh `


# Run
After you've trained the classifier on your samples, you should have a pickled model in the `./models` directory. Simply run
`python3 app.py`
to get your YogaAI instructor running!


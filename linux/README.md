# Install Ubuntu dependencies
```apt-get install -y libglu1-mesa-dev libgl1-mesa-dev libosmesa6-dev xvfb ffmpeg curl patchelf libglfw3 libglfw3-dev cmake zlib1g zlib1g-dev swig```

# Clone Gym repo
```git clone https://github.com/openai/gym.git``` 
```cd gym```

# Install Atari specific dependencies
```pip install -e '.[atari]'```

# Or all dependencies
```sudo pip install 'gym[all]' ```
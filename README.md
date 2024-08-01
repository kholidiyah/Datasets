|No.|      Video Name        | Duration |    FPS   |        Link YouTube         |
|---|------------------------|----------|----------|-----------------------------|
|Highway Traffic                                                                 |
| 1 |Road Traffic            |   05:07  |   30     |https://youtu.be/289rvo6RQDc |
| 2 |Highway Traffic         |   02:31  |   29.97  |https://youtu.be/W-XwjllUI5E |
| 3 |Traffic Flow on Highway |   01:01  |   30     |https://youtu.be/hxAUIxGUGoM |
| 4 |Relaxing Highway Traffic|   14:01  |   29.97  |https://youtu.be/a2lIM4_byX8 |
| 5 |Car Moving on The Road  |   00:24  |   29.97  |https://youtu.be/Bw7JgRkhQec |
| 6 |Highway at Night        |   10:01  |   29.97  |https://youtu.be/__6DXwL64vU |
|Pedestrian                                                                      |
| 7 |Pedestrian Road         |   00:15  |   30     |https://youtu.be/TNVlw4r8sIo |
| 8 |Shanghai Skyline        |   00:15  |   25     |https://youtu.be/EoJRvdCSwIQ |


---

## Modifying Code in Accmpeg to Use backports.cached-property

The following steps explain how to update Accmpeg to use `backports.cached-property` in the `events.py` file from the `detectron2` package.

### Step 1: Install backports.cached-property
Run the following command in the terminal to install `backports.cached-property`:
```bash
pip install cached_property
```

### Step 2: Edit the events.py File
Open the `events.py` file located in the `detectron2` directory using a text editor like `nano`:
```bash
nano /home/kmh/Downloads/yes/envs/accmpeg/lib/python3.7/site-packages/detectron2/utils/events.py
```

### Step 3: Import cached_property
Add or modify the following line in the `events.py` file:
```python
from cached_property import cached_property
```

### Step 4: Save the Changes
Save the edited file by pressing `Ctrl + O`, then press `Enter`. After that, exit the editor by pressing `Ctrl + X`.

By following these steps, the `Accmpeg` code will be updated to use `backports.cached-property`, enabling the use of `cached_property` in older versions of Python.

---

Feel free to add any additional details or modifications as needed!

# ivoryOS Client

[ivoryOS](https://gitlab.com/heingroup/ivoryos) client automates the generation of client-side APIs based on server-defined robotic control script. 
It mirrors the control Python code features but sending command through HTTP request to the ivoryOS backend (where the actual robotic communication are happening) that receives the info and execute the actual control methods.

## Features

- **Dynamic Interface Generation**: Automatically generates Python classes and methods to match server-side API definitions.

## Installation

```bash
pip install git+https://gitlab.com/heingroup/ivoryos
```


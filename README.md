OpenFoam:
A basic bubble simulation with the aid of Mistral Large https://huggingface.co/mistralai/Mistral-Large-Instruct-2407

The resulting OpenFoam code is the direct result of the convesation, the conversation ends at the point where the simulation works as in the video.

You can upload the conversation into oobabooga's text-generation-webui https://github.com/oobabooga/text-generation-webui

To compile the files yourself in OpenFoam run these lines:

```
setFields

blockMesh

foamRun -solver incompressibleVoF
```

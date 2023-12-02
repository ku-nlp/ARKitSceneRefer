# ARKitSceneRefer

### Data format
```
"scene_id": ARKitScenes scene id
"object_id": object id in the same scene
"description": referring expression
"token": tokenized referring expression by NLTK
"split": split on ARKitScenes
"id": unique id ({split}-{scene_id}-{object_id})
"object_label": object class from LVIS
"bbox": [x,y,z,size_x,size_y,size_z]
```
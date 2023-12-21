# `metadata-linked-nodes` for InvokeAI (v3.5+)
A set of InvokeAI nodes for Metadata. Collect Metadata from with an iterate node & Extract metadata from an image.

- `Metadata Item Linked` - Allows collecting of metadata while witin iterate nodes.
- `Metadata From Image` - Provides Metadata from an image.
- `Metadata To String` - Extracts a String value of a label from metadata.
- `Metadata To Integer` - Extracts an Integer value of a label from metadata.
- `Metadata To Float` - Extracts a Float value of a label from metadata.
- `Metadata To Scheduler` - Extracts a Scheduler value of a label from metadata.


## Usage
### <ins>Install</ins><BR>
There are two options to install the nodes:

1. **Recommended**: Git clone into the `invokeai/nodes` directory. This allows updating via `git pull`.

    - In the InvokeAI nodes folder, run:
    ```bash
    git clone https://github.com/skunkworxdark/metadata-linked-nodes.git
    ```

2. Manually download [metadata-linked.py](metadata-linked.py) & [__init__.py](__init__.py) then place them in a subfolder under `invokeai/nodes`. 

### <ins>Update</ins><BR>
Run a `git pull` from the `metadata-linked-nodes` folder.

Or run `update.bat`(windows) or `update.`sh`(Linux).

For manual installs, download and replace the files.

### <ins>Remove</ins><BR>
Delete the `metadata-linked-nodes` folder. Or rename it to `_metadata-linked-nodes`` so InvokeAI will ignore it.

## ToDo
- Add more metadata types
# Example Usage

[metadata_from_image_workflow.json](workflows/metadata_from_image_workflow.json)
![workflow](images/workflow-image_to_metadata.png)
<BR>

[metadata_Item_linked_workflow.json](workflows/metadata_Item_linked_workflow.json)
![workflow](images/workflow-metadata_linked.png)

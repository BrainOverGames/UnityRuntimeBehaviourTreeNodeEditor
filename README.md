# Unity Runtime BehaviourTree Node Editor
Using UI Toolkit, runtime editing is possible in Behaviour Tree Node Editor developed in Unity Engine (**_2021.2.19f1_ version used**)

**NOTE:** Since UI Toolkit(ui builder) is in experimental phase, I strongly recommend NOT to use it for production purposes.
Because still getting some weird null references while updating some configs in UI Builder.

* ## **Unity Editor Screenshot**
![UnityRuntimeBehaviourTreeNodeEditor](https://user-images.githubusercontent.com/30407235/208231411-ba3d0bf5-4fa9-496d-89c7-52145802d559.PNG)

* ## **BUT, what is Behaviour tree?**
I think this SS speaks thousand words 👇

![UnityRuntimeBeahviourTreeNodeEditor SS](https://user-images.githubusercontent.com/30407235/208232052-2f73f18a-1759-425a-bfe7-cc2bb19ed98d.jpg)

* ## **How-Tos?**
To open behaviour tree window from menu bar - click **BOG/BehaviourTreeEditor**. The first time opening up the behaviour tree editor a prompt will appear to create a new behaviour tree. Pick a name for the tree and select a location, then press Create.

* ## **Keyboard Shortcuts:**

| **KeyCode** | **Action** |
| :-: | :-: |
| DEL | Deletes the currently selected nodes |
| A | Frames all nodes on the canvas |
| O | Frames the canvas origin |
| [ | Frames the child node of the current selection |
| ] | Frames the parent node of the current selection |

Various settings for the behaviour tree editor can be accessed via the standard project settings menu under the **Behaviour Tree** category.

**ExampleScene** is provided for quick demonstration. To see behaviour tree of agent in this scene, open Behaviour Tree Editor Window (from menu bar, click **BOG/BehaviourTreeEditor**). Then, select Agent game object in the scene. (**In-progress:** Use Blackboard to store temporary data that multiple nodes need read and write access to)


<img src="https://raw.githubusercontent.com/NibbleByte/UnityWiseEditorEssentials/refs/heads/master/Docs/PublishImages/Icon-160.png" width="160" align="right">

# Wise Editor Essentials
A useful collection of small Unity tools that every developer should have.

**Download from [Asset Store](https://u3d.as/4jzC)**

## Tools
All tools in this collection are also available as standalone packages.

Jump to a tool:
* [Asset Context Menus](#asset-context-menus-github)
* [Find References In Scene](#find-references-in-scene-github)
* [Wise Selection History](#wise-selection-history-github)
* [Wise Scene Reference](#wise-scene-reference-github)
* [Wise SerializeReference Drawer](#wise-serializereference-drawer-github)

---

### Asset Context Menus ([GitHub](https://github.com/NibbleByte/UnityAssetManagementTools#asset-context-menus))
Useful context menus:
* Copy selected guids or asset paths
* Edit selected assets with a third-party app already installed on your machine. Supported apps (not sponsored): **Notepad++, Sublime, Paint.NET, Krita, Photoshop, Gimp, Blender**.

![AssetContextMenus-Copy](https://raw.githubusercontent.com/NibbleByte/UnityAssetManagementTools/refs/heads/master/Docs/Screenshots/AssetContextMenus-Copy.png)

![AssetContextMenus-EditWith](https://raw.githubusercontent.com/NibbleByte/UnityAssetManagementTools/refs/heads/master/Docs/Screenshots/AssetContextMenus-EditWith.png)

---

### Find References In Scene ([GitHub](https://github.com/NibbleByte/UnityAssetManagementTools#find-references-in-scene))
Search for references to a specified GameObject or **component** in the current scene (or prefab edit stage).
Open it by right-clicking a GameObject and selecting "Find References In Scene". You can additionally drag in any **component** as well.
![FindReferencesInSceneWindow](https://raw.githubusercontent.com/NibbleByte/UnityAssetManagementTools/refs/heads/master/Docs/Screenshots/FindReferencesInSceneWindow.png)

---

### Wise Selection History ([GitHub](https://github.com/NibbleByte/UnityWiseSelectionHistory))
Use the **mouse back and forward buttons** to navigate the selection history or open the Selection History window via "Edit / Selection / History Window"
* Horizontal and vertical layout support.
* Mouse Back / Forward buttons step through the selection history.
* Drag entries into scene, project or inspector as if dragging the real objects.
* Drag entries to reorder.
* Pin entries for quick access with right-click context menu.
* Scene objects are tinted in blue. Changing scene clears them.
* Destroyed entries are shown as "(missing)".
* Copy names or paths with right-click context menu.

![Wise Selection History screenshot](https://raw.githubusercontent.com/NibbleByte/UnityWiseSelectionHistory/refs/heads/master/Docs/Screenshots/MainWindowShot.png)

---

### Wise Scene Reference ([GitHub](https://github.com/NibbleByte/UnitySceneReference))
Keeps a reference to a scene asset and tracks its path in the editor, so it can be used in the game at runtime.
![SceneReference](https://raw.githubusercontent.com/NibbleByte/UnitySceneReference/refs/heads/master/Docs/Screenshots/SceneReference.png)

![SceneReferenceCode](https://raw.githubusercontent.com/NibbleByte/UnitySceneReference/refs/heads/master/Docs/Screenshots/SceneReferenceCode.png)

---

### Wise SerializeReference Drawer ([GitHub](https://github.com/NibbleByte/UnityWiseSerializeReference))
A \[[SerializeReference](https://docs.unity3d.com/6000.5/Documentation/ScriptReference/SerializeReference.html)\] drawer that lets you populate the property with an instance of any class inheriting the given type. Use the `[WiseSerializeReferenceDrawer]` attribute or create a property drawer that inherits `WiseSerializeReferenceBasePropertyDrawer` for custom drawing and reuse.

```C#
[SerializeReference]
[WiseSerializeReferenceDrawer]
public MyClass SomeField;
```

![WiseSerializeReferenceDrawer](https://raw.githubusercontent.com/NibbleByte/UnityWiseSerializeReference/refs/heads/master/Docs/Screenshots/WiseSerializeReferenceShot.png)

---

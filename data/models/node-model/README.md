## Prompt Builder Collections Node JSON Structure Model

```
{
  "mainNodeTitle": "collections-node-title",
  "collectionsNodeDescription": "collections node description",
  "authorName": "author name",
  "collectionsNodeLink": "https://github.com/SoftwareResearchLab/pb-default/blob/main/data/models/node-model/README.md",
  "collections": [
    {
      "link": "https://raw.githubusercontent.com/SoftwareResearchLab/pb-default/main/data/models/collection-model/pb-cm-2023-06-26-6-38-21-PM.json",
      "title": "Collection Title 1",
      "key": "decryption-key-1"
    },
    {
      "link": "https://raw.githubusercontent.com/SoftwareResearchLab/pb-default/main/data/models/collection-model/pb-cm-2023-06-26-6-38-21-PM.json",
      "title": "Collection Title 2",
      "key": "decryption-key-2"
    },
    {
      "link": "https://raw.githubusercontent.com/SoftwareResearchLab/pb-default/main/data/models/collection-model/pb-cm-2023-06-26-6-38-21-PM.json",
      "title": "Collection Title 3",
      "key": "decryption-key-3"
    }
  ]
}
```

| Key                        | Value                               | Key editable | Value/s editable | Purpose                                                                                                  |
| -------------------------- | ----------------------------------- | ------------ | ---------------- | -------------------------------------------------------------------------------------------------------- |
| mainNodeTitle              | collections-node-title              | No           | Yes              | Replace "collections-node-titel" with a name specific to your prompts, construction, and method.         |
| collectionsNodeDescription | collections node description        | No           | Yes              | Replace "collections node description" with a name specific to your prompts, construction, and method.   |
| authorName                 | author name                         | No           | Yes              | Replace "author name" with a name of collection author.                                                  |
| collectionsNodeLink        | https://...                         | No           | Yes              | Provide description page link or reference to a README file as a guide for a specific nodes collections. |
| collections                | (Array of key array values objects) | No           | ...              | ...                                                                                                      |

### collections:

| Key   | Value            | Key editable | Value/s editable | Purpose                                                                                                     |
| ----- | ---------------- | ------------ | ---------------- | ----------------------------------------------------------------------------------------------------------- |
| link  | https://...      | No           | Yes              | Provide actual Prompt Builder collection structure JSON file in the format of a raw GitHub repository link. |
| title | Collection Title | No           | Yes              | Replace "Collection Title" with a new name of your choice.                                                  |
| key   | decryption-key   | No           | Yes              | Replace "decryption-key" with secret key.                                                                   |

#

<sub>Copyright © 2023 Prompt Builder, <a href="https://github.com/SoftwareResearchLab" >Lado Oniani Software Research</a>. All rights reserved.</sub>

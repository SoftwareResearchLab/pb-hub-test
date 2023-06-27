## Prompt Builder Collection Structure Model

```
{
  "mainTitle": "collection-title",
  "collectionDescription": "collection description",
  "authorName": "author name",
  "collectionLink": "https://github.com/SoftwareResearchLab/pb-default/blob/main/data/models/collection-model/READEM.md",
  "prompts_collection_structure": [
    {
      "parentCategoryName": "parent-category-title-1",
      "childSubCategory1": [
        "sub-category-title-1-1",
        "your prompt-1-1-1",
        "your prompt-1-1-2"
      ],
      "childSubCategory2": [
        "sub-category-title-1-2",
        "your prompt-1-2-1",
        "your prompt-1-2-2"
      ]
    },
    {
      "parentCategoryName": "parent-category-title-2",
      "childSubCategory1": [
        "sub-category-title-2-1",
        "your prompt-2-1-1",
        "your prompt-2-1-2"
      ],
      "childSubCategory2": [
        "sub-category-title-2-2",
        "your prompt-2-2-1",
        "your prompt-2-2-2"
      ]
    },
    {
      "parentCategoryName": "parent-category-title-3",
      "childSubCategory1": [
        "sub-category-title-3-1",
        "your prompt-3-1-1",
        "your prompt-3-1-2"
      ],
      "childSubCategory2": [
        "sub-category-title-3-2",
        "your prompt-3-2-1",
        "your prompt-3-2-2"
      ]
    },
    {
      "parentCategoryName": "details",
      "general": [
        "headlines-general",
        "Description:"
      ],
      "rules": [
        "headlines-rules",
        "Rules to follow:"
      ],
      "codeSnippet": [
        "headlines-code",
        "Code snippet"
      ]
    }
  ]
}
```

| Key                          | Value                               | Key editable | Value/s editable | Purpose                                                                                                                                                      |
| ---------------------------- | ----------------------------------- | ------------ | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| mainTitle                    | collection-title                    | No           | Yes              | Replace "collection-titel" with a name specific to your prompts, construction, and method.                                                                   |
| collectionDescription        | collection description              | No           | Yes              | Replace "collection description" with a name specific to your prompts, construction, and method.                                                             |
| authorName                   | author name                         | No           | Yes              | Replace "author name" with a name of collection author.                                                                                                      |
| collectionLink               | https://...                         | No           | Yes              | The 'collectionLink' key is provided to allow you to add a description page link or reference to a README file as a guide for a specific prompts collection. |
| prompts_collection_structure | (Array of key array values objects) | No           | ...              | ...                                                                                                                                                          |

### prompts_collection_structure:

| Key                | Value                   | Key editable | Value/s editable | Purpose                                                                                                                                                                                                                                                                                            |
| ------------------ | ----------------------- | ------------ | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| parentCategoryName | parent-category-title-1 | No           | Yes              | Replace "parent-category-title-1" with a new name of your choice.                                                                                                                                                                                                                                  |
| childSubCategory1  | sub-category-title-1-1  | Yes          | Yes              | To provide a title for a sub-category, edit the first string in the array "sub-category-title" that corresponds to that sub-category's key. Note: Renaming the key `childSubCategory1` does not affect the user layout, but if desired ensure that any new names used are unique from one another. |
| childSubCategory1  | your prompt-1-1-1       | ...          | Yes              | To provide prompts for a sub-category, edit the array of "your prompt" strings that follow the sub-category's title.                                                                                                                                                                               |

### details:

| Key                | Value             | Key editable | Value/s editable | Purpose                                                                                                                                                                                                                  |
| ------------------ | ----------------- | ------------ | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| parentCategoryName | details           | No           | No               | "Details" is a category value that offers an optional set of content building options.                                                                                                                                   |
| general            | headlines-general | Yes          | Yes              | "headlines-general" provides the title with code snippet quote backticks 'Description: `content`' as any other new `"any_kay":` key and `"headlines-any_title",` name under '"parentCategoryName": "details"' category.  |
| general            | Description:      | ...          | Yes              | Replace "Description:" with a new name and add new headers of your choice.                                                                                                                                               |
| rules              | headlines-rules   | No           | No               | "rules" key with "headlines-rules" title provides the title with an enumerated sequence list of values for your content, for example: 'Logic rules to follow: 1. content 2. content 3. content'.                         |
| rules              | Rules to follow:  | ...          | Yes              | Replace "Rules to follow:" with a new name and add new sequences titles of your choice.                                                                                                                                  |
| codeSnippet        | headlines-code    | No           | No               | "codeSnippet" with "headlines-code" titel by default provides a placeholder directory path for the project and a code block snippet enclosed in backticks: 'root_directory/path/folder/file.ext:`console.log('Hello');`. |
| codeSnippet        | Code snippet      | ...          | No               | Enabling the 'Code snippet' option allows you to include code snippets within your prompts.                                                                                                                              |

#

<sub>Copyright © 2023 Prompt Builder, <a href="https://github.com/SoftwareResearchLab" >Lado Oniani Software Research</a>. All rights reserved.</sub>

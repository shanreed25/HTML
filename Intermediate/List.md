# List Tags
- tags used to create lists within an HTML document
- provide structure and semantic meaning to groups of related items
- list tags are crucial for organizing content on a webpage, improving readability, and providing semantic structure for accessibility tools like screen readers
- there are three primary types of HTML lists, each with its own set of tags
    - Unordered List
    - Ordered List
    - Description Lists (or Definition Lists)
- each list has attributes that can change the way the look

#### Unordered List `<ul></ul>`
- `<ul></ul>` is the container for unordered list
- each item within an unordered list is defined by the <li> (list item) tag, which typically displays with a bullet point marker by default
    ```
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
        </ul>
    ```

#### Ordered List `<ol></ol>`
- `<ol></ol>` is the container for ordered list
- each item within an ordered list is defined by the <li> (list item) tag, which typically displays with a numbered or lettered marker by default
- the numbering/lettering can be customized using the type attribute on the <ol> tag, `type="A"` for uppercase letters
    ```
        <ol>
            <li>Step 1</li>
            <li>Step 2</li>
        </0l>
    ```

#### Description Lists `<dl></dl>`
- `<dl></dl>` tag serves as the container for a description list
- each term in a description list is defined by the `<dt></dt>` (description term) tag
- each description or definition associated with a term is defined by the `<dd></dd>` (description definition) tag
    ```
        <dl>
        <dt>Item 1</dt>
            <dd>Item 1 Description</dd>
        <dt>Item 2</dt>
            <dd>Item 2 Description</dd>
        </dl>
    ```

### Nested List
-  lists placed inside other lists, creating a hierarchical or multi-level structure
- allows for the organization of content into main categories and subcategories, similar to an outline
- establish a clear relationship between parent list items and their corresponding sub-items
- ordered lists and unordered lists can be nested within each other, and you can mix and match their types
- nested list must be placed inside an list item element of the parent list, which ensures the sublist is associated with a specific item in the main list
```
    <ul>
        <li>Set 1 Items
            <ul>
            <li>Set 1 Item 1</li>
            <li>Set 1 Item 2
                <ol>
                    <li>Set 1 Item 2 Item 1</li>
                    <li>Set 1 Item 2 Item 2</li>
                </ol>
            </li>
            <li>Set 1 Item 3</li>
            </ul>
        </li>
        <li>Set 2 Items
            <ul>
                <li>Set 2 Item 1</li>
                <li>Set 2 Item 2</li>
                <li>Set 2 Item 3</li>
                <li>Set 2 Item 4</li>
            </ul>
        </li>
    </ul>
```

# 🖼 Obsidian Custom Banner Image
css snippet to allow for custom banner images per note

---

### Installation
copy the `custom-banner-image.css` file to your Obsidian snippets folder and enable the snippet in your Appearance preferences.

### Usage

1. Add this class definition to your note's Frontmatter
	```
	cssClass: custom-banner
	```
	
2. Add this `div` after your note's Frontmatter (replace <https://xyz.jpg> with your own image path)
	```
	<div class="banner-image" style="background-image:url('https://xyz.jpg');"></div>
	```

3. Optionally add these Frontmatter classes to further adjust properies like ```image size`, `image display position`, `image fade percentage`, `image border radius`, and `frontmatter shift`
``
    - **banner image size** (_height_)
      ```
      cb-sz1
      cb-sz2
      cb-sz3
      cb-sz4
      cb-sz5
      ```

    - **image position** (_shift image position in banner_)
      ```
      cb-pos1
      cb-pos2
      cb-pos3
      cb-pos4
      cb-pos5
      ```

     - **image fade** (_transparency used as image fades from top to bottom_)
       ```
       cb-fd1
       cb-fd2
       cb-fd3
       cb-fd4
       cb-fd5
       ```

     - **display solid image** (_no fade_)
       ```
       cb-solid
       ```
  
     - **add border-radius to image**
       ```
       cb-br
       ```

     - **frontmatter shift** _(push frontmatter container down to give room to banner image_)
       ```
       cb-fm1
       cb-fm2
       cb-fm3
       cb-fm4
       cb-fm5
       ```

### Example

![](example-markup.jpg)
![](example-reading-view.jpg)

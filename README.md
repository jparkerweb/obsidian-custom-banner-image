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

4. Optionally add these Frontmatter classes to further adjust properies like `image size`, `image display position`, `image fade percentage`, `image border radius`, and `frontmatter shift`
    - **banner image size** (_height_)
      ```
      cb-size1
      cb-size2
      cb-size3 [default]
      cb-size4
      cb-size5
      ```

    - **image position** (_shift image position in banner_)
      ```
      cb-pos1
      cb-pos2 [default]
      cb-pos3
      cb-pos4
      cb-pos5
      ```

     - **image fade** (_transparency used as image fades from top to bottom_)
       ```
       cb-fade1
       cb-fade2
       cb-fade3
       cb-fade4 [default]
       cb-fade5
       ```

     - **display solid image** (_no fade_)
       ```
       cb-solid
       ```
  
     - **add border-radius to image**
       ```
       cb-bradius
       ```

     - **push frontmatter** (_push frontmatter container down to give room to banner image_)
       ```
       cb-fm-push1
       cb-fm-push2
       cb-fm-push3
       cb-fm-push4
       cb-fm-push5 [default]
       ```

     - **frontmatter bottom** (_move frontmatter to bottom of page_)
       ```
       cb-fm-bottom
       ```

### Example

![](example-markup.jpg)
![](example-reading-view.jpg)

---

generate URL's for publicly shared google drive images here:
https://github.com/jparkerweb/google-drive-image-url-generator

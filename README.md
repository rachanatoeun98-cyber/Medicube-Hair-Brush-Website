# Medicube-Hair-Brush-Website
For ICT Class, using HTML, CSS and Javascript
# HTML Code
There are 4 files: home.html, about.html, product.html and contact.html
- home.html
  3 tags in body: header, main and footer.
    header: -class name logo-icon
            -ul a li(4)
    main:  - class container
                  -class info
                  -class main-img
                      * I use script in main-img to change from 1 img to another img.
                      * How:
                          <img id="myImage" src="startpicture.jpg" alt="Image">
                          <script>
                          var images = ["img.jpg", "img.jpg", "img.jpg"];
                          var index = 0;
                          function changeImage() {
                              index = (index + 1) % images.length;
                              document.getElementById("myImage").src = images[index];
                          }
                          // Change image every 3 seconds
                          setInterval(changeImage, 3000);
                          </script>
  footer: - tag p
          - class contact

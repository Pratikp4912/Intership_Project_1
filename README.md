# Intership_Project_1
# Personal Bucket List Webpage  

## **Introduction**  
The "Personal Bucket List" webpage is an interactive and responsive web project showcasing a user's goals, dreams, and aspirations. Designed with modern web development practices, the project emphasizes clean visual design, responsive layouts, and dynamic features like progress bars and animations.  

## **Objective**  
To create a visually engaging and fully responsive webpage that allows users to display and track their bucket list items effectively.  

## **Technologies Used**  
- **HTML5**: Structure of the webpage.  
- **CSS3**: Styling, layout design, animations, and responsive features.  

## **Features**  
### **1. Styled Lists**  
- Unordered lists to display bucket list items.  
- Decorative icons to represent completed (✔️) and incomplete (❌) tasks.  
- Progress bars showing task completion percentage.  

### **2. Visual Design**  
- Typography: Clean and modern fonts for readability.  
- Alignment: CSS Flexbox and Grid for structured layouts.  
- Consistent Color Scheme: Soft and complementary tones for a pleasing aesthetic.  

### **3. Responsive Design**  
- Media queries ensure the webpage functions seamlessly on devices of all sizes.  
- Tested on multiple resolutions, including 1920px (desktop), 768px (tablet), and 480px (mobile).  

### **4. Animations**  
- Footer animation: Smooth scrolling text from right to left, adding a dynamic touch.  

## **Challenges and Learnings**  
### **Challenges**  
- Ensuring consistency across multiple screen resolutions.  
- Implementing a smooth footer animation without impacting performance.  
- Aligning progress bars dynamically for both desktop and mobile layouts.  

### **Learnings**  
- Mastered CSS Flexbox and Grid for complex alignment.  
- Gained experience with CSS animations using `@keyframes`.  
- Improved debugging and testing responsiveness using browser developer tools.  

## **Code Snippets**  
### **Styled List Example**  
```html
<li>
    <div class="item">
        <span class="icon completed">✔️</span>
        <span class="text">Climb Mount Everest</span>
    </div>
    <div class="progress-bar"><div style="width: 100%;"></div></div>
</li>
@media (max-width: 768px) {
    .bucket-list li {
        font-size: 1rem;
        flex-direction: column;
        align-items: flex-start;
    }
    .progress-bar {
        width: 100%;
    }
}
@keyframes scroll {
    0% {
        transform: translateX(100%);
    }
    100% {
        transform: translateX(-100%);
    }
}
footer p {
    animation: scroll 10s linear infinite;
}

### **Conclusion** 
- This project is a testament to the power of responsive design and modern CSS techniques. It not only enhanced my technical skills but also provided a deeper - ---- understanding of user-centered design and interactive web development. The "Personal Bucket List" webpage is an excellent foundation for more advanced web -applications.

### **How to Run**
- Clone or download the repository.
- Open the index.html file in any modern web browser.
- Explore the webpage and interact with the bucket list features!




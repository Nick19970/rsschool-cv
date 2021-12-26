# rsschool-cv
* Hello. My name is Adamenko Nikita.
* Contacts:
  Email: adamenko.nikita@mail.ru
  Discord: Nikita Adamenko(Nick19970)
  Instagram: reamuccallya
  GitHub: Nick19970
 ***
 I am determined to learn new things. My strength lies in perseverance and hard work.
 I am a very cheerful person with a good sense of humor.
 At the moment I am developing my own website.
 ***
My skills:
1. Html
2. Css
3. JS(beginner)
4. Git
5. Figma
***
Code example:
***
      const tabs = document.getElementById('tabs');
      const content = document.querySelectorAll('.content');
      const tabsDop = document.getElementById('tabs-dop');
      const contentDop = document.querySelectorAll('.content-dop');
      const changeClass = el => {
         for(let i = 0; i < tabs.children.length; i++) {
             tabs.children[i].classList.remove('active');
          }
         el.classList.add('active');
      }
      tabs.addEventListener('click', e => {
         const currTab = e.target.dataset.btn;
         changeClass(e.target);
         for(let i = 0; i < content.length; i++) {
              content[i].classList.remove('active');
             if(content[i].dataset.content === currTab) {
                 content[i].classList.add('active');
              }
          }
      })
      
      const changeClassDop = el => {
    for(let i = 0; i < tabsDop.children.length; i++) {
        tabsDop.children[i].classList.remove('active');
    }
    el.classList.add('active');
    }

    tabsDop.addEventListener('click', e => {
    const currTabDop = e.target.dataset.btndop;
    changeClassDop(e.target);
    for(let i = 0; i < contentDop.length; i++) {
        contentDop[i].classList.remove('active');
        if(contentDop[i].dataset.contentdop === currTabDop) {
            contentDop[i].classList.add('active');
        }
    }
    })
***
Experience: without work experience.
***
Education: Grodn state medical university (pediatric surgeon).
***
Laguages:
 1. English(A1) + medical english;
 2. Belarusian;
 3. Russian.
***


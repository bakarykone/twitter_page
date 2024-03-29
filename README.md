# Twitter Page

I used to make a Twitter Page to train myself. I used HTML and TailwindCSS. 
Tailwind CSS works by scanning all of your HTML files, JavaScript components, and any other templates for class names, generating the corresponding styles and then writing them to a static CSS file 

## Prerequisites
* HTML5
* Tailwindcss v.3.0.0

##Demo
![Capture Twitter](https://user-images.githubusercontent.com/70897449/145606121-20cb864a-2f0d-42cf-a52a-3c3bc73cba0b.PNG)

## Installation


Install tailwindcss via npm, and create your tailwind.config.js file.

```
npm install -D tailwindcss
npx tailwindcss init
```

## Usage

```
<!DOCTYPE html>
<html class="dark">
    <head>
        <meta charset = "UTF-8"/>
        <meta name = "viewport" content = "width=device-width, initial-scale=1.0"/>

        <title>Twitter</title>

<!-- Tailwind css cdn -->
<link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
 
<!-- Font Awesome icons (free version)-->
<script src="https://use.fontawesome.com/releases/v5.15.1/js/all.js" crossorigin="anonymous"></script>
</head>

<body class = "bg-gray-900 flex justify-around">

    <!-- left -->
<section class ="hidden lg:block text-lg text-white font-bold">

<i class="fab fa-twitter w-64 cursor-pointer"></i> </br> <br>

<i class="fas fa-home cursor-pointer"></i>   Home <br><br>

<i class="fas fa-hashtag cursor-pointer"></i>   Explore</br> <br>

<i class="far fa-bell cursor-pointer"></i>   Notifications</br> <br>

<i class="fas fa-envelope cursor-pointer"></i>   Messages<br> <br>

<i class="far fa-bookmark cursor-pointer"></i>   Bookmarks<br> <br>

<i class="far fa-list-alt cursor-pointer"></i>   Lists<br> <br>

<i class="far fa-user cursor-pointer"></i>   Profile<br> <br>

<i class="fas fa-ellipsis-h cursor-pointer"></i><br> <br>

<div class=" text-center flex px-4 py-1 flex justify-center bg-blue-500 w-20 rounded-full mt-4 cursor-pointer">
    <a href="#" class="flex justify-center bg-blue-500 items-center"></a>
    <p> Tweet</p>
  </div>

<!--<div class=" text-center flex px-4 py-1 border-2 border-blue-900 bg-blue-400 rounded-full cursor-pointer">Tweet</div> -->


</section>


<!--middle-->
<section class="border-2 border-gray-700 w-6/12 text-white">
    <!--post du user-->
    <div class="border-b-2 flex justify-between">
        <div class="flex justify-start text-lg text-white border-1-rounded-full font-bold">Home </div>
        
        <div class="text-blue"><svg viewBox="0 0 24 24" class="r-daml9f r-4qtqp9 r-yyyyoo r-1q142lx r-50lct3 r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1srniue w-8"><g><path d="M22.772 10.506l-5.618-2.192-2.16-6.5c-.102-.307-.39-.514-.712-.514s-.61.207-.712.513l-2.16 6.5-5.62 2.192c-.287.112-.477.39-.477.7s.19.585.478.698l5.62 2.192 2.16 6.5c.102.306.39.513.712.513s.61-.207.712-.513l2.16-6.5 5.62-2.192c.287-.112.477-.39.477-.7s-.19-.585-.478-.697zm-6.49 2.32c-.208.08-.37.25-.44.46l-1.56 4.695-1.56-4.693c-.07-.21-.23-.38-.438-.462l-4.155-1.62 4.154-1.622c.208-.08.37-.25.44-.462l1.56-4.693 1.56 4.694c.07.212.23.382.438.463l4.155 1.62-4.155 1.622zM6.663 3.812h-1.88V2.05c0-.414-.337-.75-.75-.75s-.75.336-.75.75v1.762H1.5c-.414 0-.75.336-.75.75s.336.75.75.75h1.782v1.762c0 .414.336.75.75.75s.75-.336.75-.75V5.312h1.88c.415 0 .75-.336.75-.75s-.335-.75-.75-.75zm2.535 15.622h-1.1v-1.016c0-.414-.335-.75-.75-.75s-.75.336-.75.75v1.016H5.57c-.414 0-.75.336-.75.75s.336.75.75.75H6.6v1.016c0 .414.335.75.75.75s.75-.336.75-.75v-1.016h1.098c.414 0 .75-.336.75-.75s-.336-.75-.75-.75z"></path></g></svg>
        </div>
    </div>
    <div class="flex ">
        <img src="https://videosblue.com/wp-content/uploads/2019/07/Le-nouveau-Funko-Pop-de-Dragon-Ball-met-en-vedette.jpg" alt="" class="w-10 rounded-full ">
        <p class="ml-2"> What's new Saiyans?</p>
      </div>

      <div class="flex justify-between items border-b-2 border-gray-700">
        <div>
            <i class="far fa-image"></i>
            <i class="fab fa-git-square"></i>
            
        </div>
        <div class="flex justify-center bg-blue-500 w-20 m-3 rounded-full mt-4 cursor-pointer">
            <a href="#" class="flex justify-center bg-blue-500 items-center"></a>
            <p > Tweet</p>
        </div>
      </div>
    
    <!--les posts-->
    <!--  1er Post -->
    <div class="text-sm text-white p-2 pb-4">
        <div class="flex">
          <!--PP-->
          <div>
            <img src="https://avatarfiles.alphacoders.com/141/thumb-1920-141002.jpg" alt="" class="w-10 rounded-full ">
          </div>
          <!--username-->
          <div class="flex">
            <p class="text-base font-bold ml-2">Black Goku</p>
            <p class="text-xs text-gray-500 ml-2">@imblackgoku . 19/01/2021</p>
          </div>
        </div>

        <!--écris ton tweet-->
        <div>
          <p class="ml-10">Aussi simple que ça !</p>
        </div>

        <!--photo du post-->
        <div class="mb-2">
          <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/d5ff4d1e-e5ca-4027-890c-a7cefda914f7/dbm0w13-7b697486-1411-4662-8092-5638259cbda2.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvZDVmZjRkMWUtZTVjYS00MDI3LTg5MGMtYTdjZWZkYTkxNGY3XC9kYm0wdzEzLTdiNjk3NDg2LTE0MTEtNDY2Mi04MDkyLTU2MzgyNTljYmRhMi5qcGcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.MFYVMdGOUyGnHTv4UEp71bkdTXPfD-nS1A045v1PZ-g" class="ml-10 w-10/12">
        </div>

        <!--options-->
        

        <div class="flex text-gray-500 justify-around">
            <div class="flex">
              <i class="far fa-comment"></i>
              <p class="ml-2 text-xs">5k</p>
            </div>
  
            <div class="flex">
              <i class="fas fa-sync-alt"></i>
              <p class="ml-2 text-xs">103</p>
            </div>
  
            <div class="flex">
              <i class="far fa-heart"></i>
              <p class="ml-2 text-xs">25k</p>
            </div>
  
            <div class="flex">
              <i class="fas fa-share-alt"></i>
            </div>
          </div>
        </div>
    
        <!-- 2ème Post -->
      <div class="text-sm text-white p-2 pb-4">
        <div class="flex">
          <!--PP-->
          <div>
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMSEhUTExMVFRUXFRgaGBUVFxUWFxcXGBcXGBcZGhgYHSggGB0lHhUYITEhJSkrLi4uGB8zODMtNygtLisBCgoKDg0OGxAQGy8lICUtLTI1KzAtLS0tLTA1LS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSstLS0tLS0tLS0tLf/AABEIAOEA4AMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAFAAMEBgcCAQj/xABKEAACAQIDBQUDCQUFBwMFAAABAgMAEQQSIQUGMUFREyJhcYEykaEHFCNCUmJyscEzgpLR8DRDc8LhFSRTdKKys2PT8RYlg5O0/8QAGgEAAgMBAQAAAAAAAAAAAAAAAgQAAwUBBv/EAC4RAAICAQQABAYBBAMAAAAAAAABAhEDBBIhMRMiQWEFMlFxgZHwI6HB0RQzQv/aAAwDAQACEQMRAD8A0bCrYU9LJUdJLUzLLVomnSHC16A70oydnPGSrLmS45Z7Mh8e+irb/wBQ0WSWudoRCaJ472LLofssNUb0YA+lBlhvg4hY5bZJkTFRLiIY8bFdLgligzGF7/S93+8iLKc6eGcWNzUJto5CBOBGT7MgN4XHVX+ry7rWN9NeNRvk12x2UrYZ+6shzRg/Vkt7HmVFvOPq1WHbu7MlmfCFddWwz/s2PMxn+7bw4eWt0oZZxVx59hqeKMuH+wDvHhM0HaAEtCe0AHEqARIvjdC3raoG5+2jhZjHe8bG9hwPO48x3h+91oU2KaBiimXCODrEwvF6I4KrfqFF6G65bDRo9QF0vHfu5R9w2XyydaX1OVZJKStNF2DE4JxfKN12hhYsbhyujBluDx9f0t51WN2t6Gw8pweMJGU5UlY9fZVyeIP1X58DqL0J3P3pKjqPrIOV/rp4GjO+eyExcIxENiyqdR9ZeYI/MfyFRZ78y+Zdo64Vw+grsFM0MsBNminlRT9m0hkgP8DR6UJ3p3RXGp28IWLEWswPsOV7rRyW6WID8RYcRpQD5PdpN282GkZh2sYKEm7K8YyGx52XJbyFaBs7F8JDYCQhZRySde4fQkZL9VT7VMwlHLGitpxZhuJSVZXSVWWREVSr+0LFyLn6w10YcRatH+Srad42hJ9lyy+TAMw97399WPendWHGKMwyuo7kq+2nhf6y+B0rPNn4aXZk2Wawsy5JB7Dj2bH7JPDoet9KVnB4p7kWqSmqLtvZtAYaaDEfVDMsnjExUN7rhvNRVemxh2dNisKgBWZL4dfqjtQbfupZ7j7KdalfKJi1aJCD3TGW9GK8f4T7qquH2o0yxzzCwghEMX2iul2N9czWXTkPWglnrc/o+DsYcItu56A4uKNfYgw+ngFCxL78zmn/AJQIgbsw7odEb8EysjD+JI66+SzDEpPiW4yOEXpljB4fvOR+5UbffE58Pi7cpsOg81YO3xJq6C26fzdu2A+ZlO2ZFdBm1YXVj95CVb4qanRbPDRyYgjuxTRRIfFrrKQel5Y180NCXxZjaQAXJYFR1aRENvV2NXp8GI9lyQjXsewZ25mXtY55L+9ST4npT6y7lGvXkTWOnIBooqfhjUGMVKRrVeUE8vpTEktqhzYu1QJsdrRJAylQYWepcLVXsNPc0cwrVKJF2T0Wm5xXvbAVExOJoQrJDYq1MPiaHTT012tWUU7mEjibV7Hjars+1I727RSRxAIJHmBwphdsRg6yIPAsB+ZobX1O1L6DG8eEC4jtO8FvnujFSA7XZltxZJAX1H94BzFXbBb3TRgdqizrb24+5IR1y+w58QUHhVZx8okQMO8VubDXMp0dR4kaj7yrTOwpshEJ76kZorG2dLXsp5MBcjqoII7oNZWqU8eTy9M1MEozhz6F9xW29nYpAMUAotcNOjR2B5rN7Pqr1W8futs0fSQbRhjOuVZJYWQ3Gq6MDlPAnU8+IFENnl4wXhbPHfvgC5RuP0kROh53BFxazWo5g52Zc8WHw83jGyxt6pIvd8sxrkMqnxJc/wA/Ybi49MxuaTsZLq66a3R1ceIzLoedjwvfkatW7m9mQ91l14i90bz+yf68KtG1NsOn7TAhB1eNnUeboMo99VbaE8GIF/m0MnQwvZh5Br29CDSWVRUvVP8An2L020c7eZY5UxcIKZGDMv2RwYg8wAb+g6VboNrouIXNYw4tNQdVWZQEdfIqF89TWc9s0XdRiy2N4JwQ1uByvqbed6e2dixLh2hJKmJhlL8V4dmx66ZVJHHKakJuEbOSimbLFizFaN7te/ZMTq9gTkN/7wAH8QF+tuNo4CHGQ2NnRgbHpyOh9xB9arO622VxkJws+ki+jXXgVPJlIvcdAa82fj5o8Q8QN8QurRnupilH94vJJrWuNA3HTUB/xo5FTKNrTKJvXgpsMy4eVi0IIyE6925yrc8UuTpxHDhoId3laOJBc3AVerscov5knytWl7xdhtHCuALSICcjaMLaOLdONxyI5UC+STYeeWTESamBjGoPHPlHePSyMPVm6UqsPiTST/n+y3fSs0TAYVcHhFjHCKPU/aIF2bzJufWs323MTgJSeMmMQ/wpGx+JNXrfbGiODLe2c6/hGrH9PWs/3pBXDYOHgzZpWB43lJax8iwFWamfmaXSQONAHDf2l5X0SFEPm/ZLy8Axt4nwFaRtOJotlSIw+kbCYiZ78c2TOQT4F1X92qZuPspsZjGuPoY5Wd+jZWKxL65R6B/CtH3m78eMH2cFKP8A9qv/AO18au0sJJ7peyQOSukZtHjBSlx9VxcUa8fEE1qJGTuCeIx16ijEXNQDJXSPRAPksezno9FNYVUsHPaifz3SuMKLoK4jHW51BfHXoTPi71HGJrtHGywM9NSz2puR6g4ieocEuLaH2LlOcfTqUvop+77J8ONEsLtASAC/taKw0VjzWx9lvut6XqtzTi9ri55X18aZScoSQMwOjoeDj9GHJvThWfq9FHIt0Ox7Tapw8sui8Q7AjlNh2ay8Msi9kx8pUF7/AHbDzNQcfuu0IsTPCFYsr3DqrXvmEhzZTmsQMw11pzYG8qBVTEDt8OdFkNzLDyy34kDhl4i2l/ZrSsDEcgMcvawsO61wWAPAq9iGHgR68qz8cZSVW+P5ymPSdclIwDNKwMb9ljFW5yWUTIOLxqbqRr3ojcAm4+qSRwO8UWe2Li7GTh84izBCfvgd5PJsw040/t3dq/eWM6HMsuF7kqMODdie6x1NyhDG9rWNVjF7fRh2eMysRp85iDISRpZ1OqOOaHXoxo5RlDn+3+jiakavgnzIGWQSKdQ4KkMPArofSoe0t3MLiNZYELfbHdf+NLN8ayODaMmGbPhpjYkaRkBnJIABhN0kYmwFgDrVw2ti5zDbFy2ksO0WMZY4s3sIQCTPMwPsElBxKkWzM480Jwba4AlBxYD3t2bh8OSkOK7cg64Vx2zA/iQfR2H27fiqnwtJn7VIW7PKVlBYN3PC3tAeZOp41oe725BkAMi9jBxEI0Zud5CPy/PSrBtnEbOgj+byOiEcFQF3U8jZAWHmaW8PcnJRSRYpVSuzKY8SVAmR7PGASw4sgtlcdSNAeunhRfB7VfHYyBp3OHa6qjxBbiQHuNJmBvmNlKi1rgXOtBcbg4vnQVJVaH21IutjfW4bVQOIBGhb7oo5idl3iYxLZo7MGHEHkSfMe+1LPJ4UkW1uRNba8rzv2iJHiYmOfs8yxzZDlZgrElTYG4uc0ZLX7pFTNwcd2eOZRomIhJseUkRva3Wxkv5V0+G7baAdLA4nCxzoT7IkyWAPgclmHMOw51Sdo4swzK8ZZRmewJ7y5o5onU9H7uv3iacdqe9d2/zwUrmNFz2jjv8AaOP7EG8IOU9OzTvTMfBrqn71B96do9tjHkGqxKWHkozfEKh9a93cxUWHwzMZE7WfQkMPo4gScvHRmNzbjly1xu4iu7SS+yzd4H7I1K+6y+lKZpU+fXssgl2X/dnZYwGGhw1x2rLnmb8IXOfId1B5360P25tIjZ2Mnvbtu1VL8QiJ2f8Akc/vVCxW1Xmvk1mxThEHELEL5B5G7SE/ZtUH5UcQsUMWEQ6AKvUkDVifMJY/4lPrK5uo/b+fZC8vKrZnQpV4T42roCtZGQzyugaQWugtdIORyWp04io9qVcRBxpa4LVya4JqWQO4jEUNmmvXDzXpgtUIdB1DKzp2ij2kvYlT7QVhqrcwRzA5Xo/jt0pciz4VvnUDi6lbLKBbgy6Bj4i3lVcqwbobxNhW7M2aJzorGyhyeFx7NzwbkTzvovn3R88RjDtl5Jfgrxl7Fu+CisbMHBXXgGGYC/Q28+VWzdHet8E9iTJAx7yXBIJ4lejfBuB1savCRR4pC0arKR7cch7OdD0LC4fwzAg8cxqq7Z2VhkN5IDEf/WiGXyEq90+l6zMs2p+Il+umaWJJR2Nmq4XGRSIsscilGFwb6EHz4fpQfeXYODxa5nZI5LaSqyhvJtbOPA+lqySaDCjVYYX8VY/qor3ZOzjip48PFGI851ZT7CDV34kaDhp7RUc6i1W97VDv3C8KubLNulu2IJJMSQjsjtHh+zGZJHGjz5QdQvsi9tcwvqDVsTBQ4ZfnWNcXUkop7wUtqSAB9JK3EsB4AACnJMZDg4u0C91focNCvFlj0st+RKkluGVVNZxvBtWSRjPiH73Beapf6kKH2m6sfjawtyzjjqK5f0AjFy5Dm8m+80vdjLYeI8LWOIkHppEOOt/XlVAxe0EFwBz1Cam5vq8htY6E204HQ1wQ8xOmVSdRclj+NuJPgKeGzEtaxHipy9OnkOPSl2tzvI/wNRwyryoYwGLvIrZTmTOAGsbHuEFrHW1jbxArSfk/xPbvLHJa5jINuYJFj4Hj7qzN9hm5yyEXUAEgXBBup0sNBpw4AdKv3ycN/viNwzwyBgOHaRugNvDiR+KpKEXOLXQE4yjF7iwbLw5XF4Mc0hxCekczItDNibHim2jjGlRZRHK5RXAZUZpWNwp0vfPqbnvGrYmH/wB+UfYhdj/+WZyPyPuoJub3sRj5ORxMig/hll/0PrTTVX9/8FUOf1/ktDwKVyFVKEWKkAqR0I4W8KyvemD5vO+Fi7sZVZAAdVSQkFQeQzI1ulwOArSsXtWONWZicq6MwVioPC2a1r30tfjpVO3v2Q2I2lFECVD4dC7C3dRJJs7X6gNYX5sOpqvLDdHlEi6ZN3HwgRHx0xsiqyx3Fu6P2kluVyMoHQEc6A7w7ODy/OcaXzSD6DBIckhUn2pX1MSmyiw1sg1vcCzbZ3pghURxIjrFkABtlBH7JVHG/dvm5BSdTlvmm0toPMWd2LSTas3AiO5Fh9kNYqByVW6g1IcOMcff8tgSfDlPoi46RJG7iRrGp07NbBmGmbMbs4HIsSTqbm4twqU4sdPJFWvjxqMaMnJkcpWxgR10IqlLDTgioytyIRirkx0Q7GuGiqURMGla4YVOeKo7x1xo7ZHJrylSqEFXjKCCDqDXtKodDm7+2WR1UyMkg0imB1sf7t76N4ZtD52J0XZu+YHcxS9mdPpUuYjyuw9qP1uPGscQZ+6oL8iFUv7woNvWj+z1myBJ4JGRfZkzL2i+Fg2ZvPj4GsfU41hluxte8f8ARqaebyKpr8myDB4eZQ/ZwyKw0bJG4I8DbWoOz44IRiMUFSJReJCiBe5GxUkAAXLS5gOoVKyyETxn/c8QQzsqDKSpDyMEXtEBF7FhfMCa0HbmMigjXNrh8KBHEnHtp1GW9vrBOHixbwruPKnBySLHCnQE25jhHaWUfSMAkMIN+zTTKPMixJ/eOgUCj4mN3xD9qbshtpcKqkBgq3/FqeJt5AWHH7KM+Wf51HJPLGHELApZW72RJScubwYLcjiAABWMTPkxCF1Y2dTMhBDHIyrlYcQbAgjnYVRGEt7v19RiDS7/AET+77Og8AbGmI8JJm7jBr/Vc5SfAMe7fzt51rex9o4bFh4sNBEY0A7kgWNWVuDKmRrjlqAb8tRcNtzc5Ddog8B17jgvCfESJm7Mfi08BVngtK1yW/8AJTdS4KnseQJiI86kWkCyI4sQG7rBlPDutVo3O2b2O0pYhqEkkt4I0MB/zLQsQi6x45GRbBY8UtjYcFUyC6yJ0F7r4ci2y8WgkxeIdiEu6tIL37NSqOVtqWZYoQoGt5Ra9qmOHm/IGoyWgxtjbZw8ckyd6fEvkwykX7iDKrn7gu0nj2ii+tN7AwfZQpCuZr95ip+knZvabNpkjvpnNs1tOWYfszZsuKmbGYgCOy2SJ7ZMNEPZVhwaSxvk4Am7fVSn9g7fxLMWSIlCQ1uzYlweN5jxksRqe73bWAtZtQ3cvoRnkUKX1CeLgknkbBusaQqkLN2YYkXkYiNToBpFxy/W4VWd5trStiJVGWNixgVbkgLE0jmWQ6dwKxkKjko4m1XbA6SO7nK8suYKxAIVQqILX+ygYjqxqifKAFixcsq8ZOwiJymRVNmlnLKAbho4sMhFjcMRzquUN0WvSyyPD4I+3Xwz7O7kLx9m0TLLKsYeRJJCkkl1JN2s5INje2lVGMFiWIsWN7dBayr6AAelXfejZyx7NQfRntJoSDCX7IqM0i5FdjkU2Jyg5dSRxqpxx0zp4K9wlrMlVE5jjqQsVdpHT4jpwQsZVK7yVIEVeFK4CxjLXnZ0/lroLUJZBeKo0kFFzHTEkVdOplZpUqVCWCrmWMMLEX/01FdUqh2whgttzx2Fw6j6rAA+hAt/ED6Vc9hby4OayzQBX+5mDeJ7MN3gOqFvIVnleMt/zHUEcCDyNJ5dHjlylyM49VOPDZqMWDVsZE0QhIRZJEkRmkKmwhTOGF0sZixF/wC6NVbePai4uQdnIFiiGWFGDNcDQykjW7a2PQ351B2ftcxYafOWd8Q6Q6EBxholLSd7TVmnZATrxN9L0bj3uikAWbspABoMVApyjkA6gAe80llxuMNiX6Vofhki3dlbngzREkBjEGXNZrIrs0iOOa98ygnwjHMU1jsWZIw0y/TRhR2n1mh4Wfk2W9+q2I1BFXBMXhGIaKCMZgUkEExfPE41yxnuhgyo4tr3Lc6qm09myQNmCiRHLBXyM1yfaQkkFOFirC6nQjSpB2hmDT4ZL3e2o8DpLGRnQ8DwZTxU+BGngQDyrS8R8pOH0EcU0jkaCyjW3CxOY28AfCsWwjWORs65SLgkg5T7Oo49Lg6lTRqFAhuoCtfiNDfrfjXFlePgteJZeQyMbjAJJTh5ryWBZy8cbvJ9EoaORMr3d0suU2sBwvVg3TTCy/QRTXGH0AQlWkkTRpr27wW+VcvAEk+0tqxtLb2JmSOJnGRSSzWPaNplUX8i2vHhzsRA3Q2XP84XIwRY3WRptAiKD38xuLFhdQOHmL1d42/7i3/F8NO+i77VixMZCgx4bDx6/OZnE7AA8R2misdb90sb6tzo3h930YXmmnxBOvflcRm/SKMhLehoj2rSEZQRHrdmFs4sRlVTrbW5Y20Gl73EmNAAABYAWA8BXOQLPNnYOOMgRxog6Iqry8BWbb0JNjMZi8LhwzDtSzsrZFRxDh4kzvyACuQouSTwtWnwkA3OgAJPkBWNx7aKrHJG7rNiXmlDiwAMruzgox75WJkCnKwDA/ZYVbBWqActvIf34xkZEODit9AVZwuqpliZEjvzaz5vAAXtmFVxI66ggtoOpJuSSSTckk6kkkkk6kkmpSRU9jhsVGPnyvJKxpUp+JK6WKpMMNWFaR6kNNzQ0QSKvJYaGyzbwCBHTyRVKWHWpceGrqYG0FtFTMiUVmhqNJDRWC1RQaVKlQFoqVKlUIKlSpVCDcUViTqbm+vLwHhx95pw+GpJsAOJJ0AHiSbUq8jZw+ZSFsNG0JBNwSARYG3A68TpqCBlaXAcab8zLbsl48ACw72KdbM6gEovHJHfRR1c2LEaWAAqDituyZmZVylvaYsGDD76sQr/ALwNuXWgJw4Ptd7xc5vz4ele/Mo9Po1IzLmAABK5hnAPUrcetZz0eRvxJS5H46yC8sY8HOMxaMA+pkN+6gOQDtJMwGZj3SiqRlLd5SDa5ong5Qyg3/rkac26MM08DYYyMMoVy6BNQkllAyKxsCRma97jU2oMZGwzkZS0fHTioJ6cxe/Dh0tVeWKlSS5o0dNl43Pq6DlWvc7a+FhGWZcr5riU3ZfDTXKRci4FU7C4pJFzIwI8KIYHZDYomNGCvbMoJIzW4gHrzsf0paFxkOZds4GgYPfjCSTCFTIWLZQ2Q5SSbDx94qzVS9z9zPmziaUguB3VGoW/Ek8L+VWjae0Y8PGZJCQLgAAXZ2Psoi/WYngKZXJmzSXCG9vP9A0QJDz/AEKW4jPpI4/AmZ/3apu2cEsceKWVZhNNK/YlbmKQ6tAcxBRDGqgHg1oza4te1bIu8kkko+mAVSAbrCrASCFepsUZm+sWHJVAW9cWbCsdLxvHJfoocLIf4GarVzJKymfTZSoMJU6PA0Tw2DqdHhxWjuMtYgKmz6kxYCjCwinAgoXIsWNAsYOmZsLR4IK4eAGuWFsK4mH1qWkWlEGwte9hUbA2UCZYKhywUcljofiVokwZQMlpV6RXlEVipUqVQgqVKlUIKuwKbdwBckAdToKB43bDdoojN+nQ+JBGv8qFsOEHLoPnEoDlLKD0JtUtFqrSSBRdiNeJPMnWrDuVsKfGOewYJCmssraxqONgObka2BFuJIFr9k1BW2GsW7hD8g70fXPf0ysL+8j30Sg2d84vEtu1KkxX0u669megdQRf7QQ8qIbdxeEhjXC4VcxaRTJO2ryFLnjbUXPgovoNar2JxjQypKhsUyt6Akn3cfSsrPPfkUkbelxPHgcZDGB2YJTeMOstzcLoxI4goRqRYgg66GpeHx82HcOwN0NxIgJsR9pOI9Lijm9UWSWHaEPdjxNi1vqYhdW/iylvNHPOrzgsNhtoQrK8a5+DFe6wYce8NSNbi/IigkuaLVNKJAw3ylbPdATL9Jp9Eis7Fui5dLeJI8bV1shXmLbRxfdVFYwRDURpa5cD6zkC1+fLS1N7A3Vwk0UWIyvaRA3ZlgRryJCgm3AjzqwYpRLNHAPZS00o8Eb6BPDNIubyhYc6sSbdC0nFdAvDbQaHEw4d/blV5JuBtLIbqt+ihMg8LUe2nhu1glj+3E6fxIR+tZPi9tNLi5MR9jEHL+GNrJ7wt/U1sEMgIVhqDYjy4ihjJ72FOCUU/qUnZ23kePtUcTx5czGJW7VNLnNCLlgDpdL8R3QLkUreD5SJZARhrQx/8RrGRh1HFU+J8q82jsmbAThlJTUsLXF1uQpB6i1vLwIpza+6sW14mmw1osYgLPENI5/vAfUcnieF+PG9M49Qt1SF8mlpbogfcveFsPihIzlkmIWVmJa9/ZkJOpKm2p5Fq1z/AG3AJRCZo+1PCPMM1wCbW5GwPur50wAZGeCRSrKSCrAgjkykHhT+ytpNFOuljG6sCOJyEN8QPjTbp8ilO6PpeKWncwqtbH2/DiFzwyq6+B1HgynUHzoh88oaB3V2Fs1NSNaoK4uuZsTUojkezy1Bma9NT4iuFkoqKt1mZEV5an3SuDHRUV2N2rzLTuShu1drJBp7T8lH+Y8q4+DqTbpEyRgoJJAA4k6CgWP3iUaRDMftHRfQcT8KCY7HyTG7tpyUaKPIVFtQOTGYYUuyRLiZJmGdibnyAHlw0qZstMzNJbwXw/oWFQsOO67dFsPNtPyvRjBRZUUeGvmaPGrdhzdKkGN0dz5NpzMzEx4SI2kl05alUvpm8eCixPIG77wbdjSNcJhFEeGQWVF0z2+s3O19ddTxPhB3b2vJicDh8Fh0SMIpV7uEE0oY+HPjqRcnyoRj8FLFKIpo3jkJ0Vhq1/sWuJB+G9ZueUpyf0NHBCMEn6nWBw2plYlmPAnkPAcv66m/GPa7eQqXMsg7ioVPC76W/dGt/A2qzbE+Td5FzYiZ478EjVA3mxcNby4+VLxTbtjWSSjE43BC4vCz7OlNr3MTccjrlKMPEdw+NmpvcTa7YbENh5u6CxjcHgsisVvfoDcX5gg8qtGy9wosOyvFicUrKSQb4c6m973h14mgG+26OIEr4uI9vmsZFVAJAVULmyrpJcKL5QDpwNza5q17iykt3syy7uYZsG+KhdiMPGFljZuCq/amQX8OzuR1JPOnNnbZjgwnzzFOIjinMiqbl+ztaCNUHeY9mFYgDizGqHtzfGWTCphGibMSval8yZoVsSrXW920GmpF+FQMPDPjZw7kyyvoo4ALyCjgkY6DTmbm5ru5RXPZxYnKQM2Zh52YLGua+gJvd7cCFAJ14+FaVu7s7a0agGWBEtokqPIV8ssgI8rjyo/u7sBMKvJpCO8/6L0X86M0Cvs7OfG1FN3h3ex2JIJlwzZb5RlkhGvH/iE8BztVWg3c2lgpUmSEMA2rROJEAJsQ40fLY6nKbCtbr0G2oolFXbQHiSqj5l+UWb/7tLJeM5+yb6J+0SzRIDZ8q5uF+AoJjVyzI3Ww/Q/A0X+VafPtbFnQd9R3QB7MaC+nPTWhO1x3VbmD+n+laOP5BKXzEGLESQyFo2ZGUkBkJU6HqKvm7fykupCYzvL/AMZR3h+JRx8xr4GqJjx3yetj7wK5XCsUzjh8dK59iNJrk+g8NtFXUOjBlIuGU3BFdyYqsG2Jt2fCteJu6T3kbVG9OR8RWjbv71x4ru+xJb2DrfqVPP8AOji16imXHKPK6LS81dCWhxkpNPVlFCYAZK4KVO7K9M4kZFva/IAcSToAPM1xtJWwktzpFV3l2u0R7JNGK3L9ASRYeOnGqpCmdwPtHU/mb1P3icmdrm9rC/I2426Dp4U1sdLuT0H51VF7mjQ2eEq9UT0wEY+rfzuaByLYkdDVlqv7QW0jef561ZlSXQGNtvklRw/QqPtuL+X/AMCi9R0h7qD7Nj/0kfrT9WRVICTsM/JZsqXGTyYeN1QKTI7NrZbhSVUas17cwBzPAHR95tqrETBA7SSAZZcTIc0h5FFIsEXTUKAL30vc1jG6u3HwWMMiMVzCSNiLk5X6AcwQp9KuMO0Yn4SLfoTY+5tayNVcXUV2a+lipq5PoLbI2k2HfOqRs3IuCcvlYix8asUW/wBKPahjPkWX871RZNpwrxlTyBzH3Lc1Cm3gQeyrN4nuj46/ClIqa6HZRxvs1KD5QF+vAw/C4b4ED86KYTfHCvYFmjP31sPetwKwqXbkp4ZU8hc+9tD7qZTEYiXRWkb8Pd+KgWq1bl2yp4Iy+VMs29GM7XH4hxqCwseRC9wfBB76f2Zt8wNmjlEbWsb5bEdO9pVfh3clfWRgPxEufzt8anRbtwILuSQOJJCr8P50E8mP6l+PS5EuuPcvGD+Ugr+07B/EOEP5kfCrBs7f7ByaM/ZnxKsv8Sk/G1YvjsZhk7sUSMftOCR6BuNRINlTTG4jsD9ZgEX3W4eQo4vi3/cqyaaLdLv2Po99sYdYzKZ4hGOLl1y++9UnbfytYWK64dHnYX1IMcYt1JGY+i2PWsjxuAjiOW4eTnlGVV9eLH3UNxpyxm3PT31bFp0US0zgm2yDtDGPiJpJX9uWRnNr2zOxJtcnTWiG1h9H6j+X60P2Yl5B4a/yovikzAD7y/nWnjj5WZM5eZAnaa2ZeuRR7rii+Giyoo6D48TUSWPPP4KBf8x+dEKsgqbYE3wkBNpwZGuODa+vOpm6Zti4STaxP/aw/Miltgdwdc36a1I3JwvaTuDw7J9emay/qaXzSWO2X4cby1H6mllqakamcLMWRWOhtr4MNGHvBFeuavTvkypR2tphOLDUH2tKAztyhU2/xCup9AQo8S1XCDD1RsVOuQK/CdnF78DIWcH3n8qR12RqCivU2fg+GMsrnL0RnG1B3weo/ImpWxV7rHqfyH+tebZgK8RqrEH+vSndkD6P94/pV2l5SJrVtkyYDQnbUViG66HzH9fCiGFkvdeakj0+r8K9xcOdCvu8+VMyW6InF7ZHryWUNy0v5Hn6aU7UfDjNGAea2Ppoaj4DEWJibiNAf0/lXbom2/wD8ctpG8/9aNYBO1A1QE/bbKL+ZqBtiHUPyOh8+VN7NmIutx1F/jSOpgzR0WVJ8+pbI92pDxZAPNj+lSot2B9aQ/urb8zQHCY+RPYcr4A3HuOlE4d4phxCt5gg/A/pWZOOX0ZuY5YfVBvD7EhT6mY9X73w4fCiCi2g0HQcKrse85+tF7m/mKeG80fNH/6f50vLHlfYzHLiS4DhqDPspJDeQu/gWKqPJUsKhpvErHKkUjN9kW/Qm3nRJcQQmeUCPqM2a3rbj4ChUZwC3wnwe4fAxx+xGqnqAL+/jQbbW3OMcR83H5L/ADqJtbbjSXWO6p15t/IeFB/6A6+Q50xjwtu5i+TMktsBUO2pJwX1/T+dWrA7DuO0nORAL5SbEj7x+qPj5VVNuYsSzMy6ILKgtYBV0GnLmfWncFOXHoZusbjj+47sVPabyH86J1F2Ylox43PvqVWtDhGBN3I4SMAk8ydfQWFdX5f1/Wte0zA2ZmblfKPTj8T8K6c75IG2ZNVXwv7/AP4o98nijNMedkHpdif0qr46TNIfOw9NKte4C2Mnl+RArN1z/pyNb4bH+tEs2HNjIvRyR+8A/wCbN7qcY0wzfSv0yp77v+lq9L0zpZXii/YytfBR1E0vqX6eeOIZpHRBewLsFBPQX4nwrLNtRk4SE9BHfwulvztR75QtoMsjFCRkKxKdNLr2jkX4XOVT/hiobRLLB2QIv2SemgKn3is3V5rkq9Gb/wAM0uyDb7kim7Qk7Zbn2yLN4svBvUW9b9aY2V+z9TTs8ZRiGFiDZh06Go8EgSQqdA2o8+dN6WaUqFfiGNtX9DjHsY5FkHAixHW39fCiEbhgCOBpjFRiRCBxB9zD+vjQzBYsxmx4cx0PWnN21+zM2ty90GwLUN2tBwceR/Q0RjcMLjUUwkysWjbjwI6jqKKSTVAxbTsYws4lUo3tW9/j50PW8b68QdfKvJ4jG1uBHA/kadmmEi3OjjnyYfzqmXKpl8PK7QdVWhYZo1N+TqrK48DwPmKOYLC4TEcEyNzUMwPprYj0qubD2+ygQSJ20ZICoRdteAXS58K0PYfyW4nEssnfwkfH6YZpfDIim45+2QR0NZk8U26XHubePU4lG3z7eoDfdiPk8g/hI/7b16m7kS6szsBy4f8AaLk+VbXsvcHCRKO0DztbVpWOv7iWQedr+Nc4vcHDF0khLwsjq9rmRCV1W6SXAAax7tuFcWny+sjj12H0gZ9Buni0S0WEWM8hJJDHfzsxb3iqlvHu/tCORFxEDkyG0QitIrG1yF7MnWwJ11sCeANavtvYWPizyh1nUAs3Z5o5LDXSNswc2+8CeQr3YONbEx9kWtcqY5Brkk9qORfUC44EEjmavWmguRV67K+OKKJu78kuMns05XCp0azykeCqcq+pv4VomzvkqwEK6CYyW/amVs38Isg8stWzY+O7aMMRlcErIn2JF0ZfEX1B5gg86m1aoJFEs05O7MY33+S7GFS2FmE6gaQvlje/UMO458wvhWIY7AyQyGKWN45F0KOCrD0NfZ+PlyRuw4hTbz5VQt4cDDjkyYqNZCPZkACyp4q44eRBB5iuwio9AZJyn8zMJiSygdAB8K6vrbwvU3eHAHCSyRubhTo2gzKQCptyve3mD0oLs2XNnc8z7gB/rT25cUIuL5H8ZPkQnnwHnXER7OIHot/U6/maH4qftXVR7N7D9TUvaRLZYl4nU+AFBu5bD21SIGDW2aQ8F4eLHhVs3Rfs4y1rs5VFXhmY3Y+QFwSelVl1zERp7K8T1PM1bdgwrGhxEuigERjrfiQPHgPWs7WNbdpsfDovfuJGLn/3vIyKQ2QZtQ4uo4MDcak6U/FIbWOpBKk9SrFb+tr0N2VG085mOiq2Yk8NOC38AB6VMEgJYjgWYjxBYm/rxrmjk9232K/i8I7FL1bf3L/vluiJlaSM953TNGTYF2ZYwyMfYPeFwe6fu3JOcSYR4n7GUtDLGSEkIK2HHI4PAcxy10uDrsuKnEiMhNsykXHEXGhHiOPpQTfl4sbgsPOyIzZsjkcVcB1kUONQA6nz0NFqMcUtwOh1Um9nZl22WawE8dnGglXVHHQ/1fwqv4mDMMp/dP6GrrHsuVImaKUMokydjKMylSgYG/LXMLW5cahNsMyoX+bzxre3aRxvNASONio0t4EAGqMflH8jjNcv9lLWZ43uePA/eA8efnT2OjDjtU1+0OY8aPf/AE3PIxjiQzt9iMM7KOrLYMnmdKZx25m0MKplfCzIg45lupHjb9aehltUzKzYFB2mV3DYpkNx6g8DXeNnVyGXQ8x4jgRXM0RGuVgDyIOnkTxFWzd35MNpYuxGHMMZ/vJ/oxbqFPfPoLeNHu4KdvNlWkxPaKFYd4eyw5+BFXbdf5KsVicsmJPzWJrWDLed/wAEXK/VreRrS91NzMLssEqRiMSRrM6rljPSJeXncn8qvuxsEf2sly7cL8QP50LlYSjQO3R3EwWzlHYRAyW1mks0p6976o04LYVZ6VKhOipUqVQgqpEWxjhMS2UfRPIrR/dubtH5A3I8GAHCrLtLayxaDvP05Dz/AJUMwAfEFyzXIyEdAQTwHLS9QhNjsuMbKbZ1AkU8GZVujr94DunqAuvdAqTiNo5cRFABcukjk9AhUAepY/wmqxsTGmXaeI1uodgvh2SiI/8AUGodt/bYTFYiQXupSFbXNwqkmwGpOeZ1sNSRaoQP7zbeRR2YOhOpHOx5eA60KquNsTHlzNNhZdRZQpicIp1sVVy2Y6X00tYcyXF208RCzApc2tKjQsfw5wub41CFO+WnZ/7DEDneNvG13Q/Fx7qzT5x3Ag4XJPieXpWx/KEVxGFlAvZY8w/EveJ+FvfWOYTClyNDbr1txt/WlHEFknZcdjnI0Gg8SelOzMblFPfb22+yPsg05iJcgCrq9racEFe4SHL+t+JPU/yrmXJsjQeDC8krfRLwOFSNQXGnJBoz+J+yvjxPLrRTDQSYpgz3EYOUBQT5JGo1J5aAn8qiYDCGQgkMQdRe4Dcb9+3C4INrny41sW6GBw+GxMmob5vh0LysAFRmJd1QcEVVsCeJuQSbaINOT5NV5Y44+XkzzaMDxu2HZOzWMqDFe5uUVxnI0vZxprqDe/Jinppmllmke93ld7G5IEh7RVufshwv7tLsq0cWOMYraee1WWeTI3Mtwx561Vdj7ZZIXje5ilyudLlJRYhx5jusPI8rGdNNZGPRWPwNQ9mpaNf68P0qjWy2pDPwuG5yf2Juy8J84nhiVu5M6q9jxRQzsQRzCCQD8RPKtN3r24MLEqxgByMsagCyKNL26DkP5VTfk+woONBAFkikfyYlEB9Q71C2/jmxOJYqV7zZYy7BUVVvZmY6KoALn1trYUkm9ijH1NOUU8jcukHN3oZHwskpn7BDIzyy6NJIQvcVS3dQBAHzHMPpG00ojs1MRcSx4YAkd2bGSqHKkcg4ZowfshVHhUbZOAlaOKCGFzBBcK0/0KzSBrmZ8wLFSwzKqqwPdvYCxPwbsszZ8Time5uY4bxL5F7l28wVv0p5UlQg+XZI3chE0ZxOKyPKssoHfMkUfZSPEOzDAKDZfaCgm5pbU2wXuqd1evNv5CucJAkeEmijVVVJ5AFUAABpe0FgOGjihdECEth4PtHufZXU+J5D+ulWuoOxsN2cSg8TqfM/6WqdUIKlSqPjMYkQux8gOJ8hUIPswAuTYDmar+09tk3WLQc35ny6edD9qbVaS5JyoOXL1PM1WsdtMtomg68z5dBUIFRiVL5b3a1zbW3mase7hCpI50A4nwAJP51T9iQ2Qt9o/Af63o5tuYxbLly6NL9Gt7nWVhFewIJspLcRwqEB25Q7KGXHSKQOzeQ8B7ZMrAFiBe5PE9Kk7i7vXJxWJs0xdmCC5SNnJdzrqz3ci54DQDiSGwEkk73mbOEAyJYLEhuLZYxoCLaE3Ydav+7q2h82J/T9KhApXEkYYFWAIPEEAg+hrulUIVvaO42CmVl7LsswIPYkxDvCxui9w8eamsG+U3dI7JkijhfNFMrFXfKHBUjMrEWB9pTew48K+naDbbCibCllBDSSRm4B0aF5OfjCKl0Sk+z5X2XstmPcBc82+qPXh+tal8nO5GGlzyYkdq6MLRn9lYjQkcXNw3HTThWm4/djAT3zQRqx+vGDE/8AElifWoGzt1Xwbu+GcTI4AMcxysLEm6yKLGwJsGXXm3Ol5Rk3adjXix2bUqAnyoYIdnhZVAUxu8QsO6A8ecaDkOx4eNRNwtnrMuJWS7KwQPrq+ZmZ8x+9z63NEN/McrYXIytFIJY27OQANa+QlSCVkAzi5QkC+tqkfJ3FbDu32pD7lCj+dVZL3KwoNeEzP9oYQDGToBYZjYdMsjj8itO/MambTt/tJrahpJU9SM5+MZFGVwgp7TT/AKaMzWY6yt/WilY39lJ+BvyNe4T2F8qVKlviP/ka+Ef+i3fJ5+3n/wAD/NQLdz+34L/FP/jalSqjH80R7J1P8GxtxNIUqVWPsUQMwv7PHf8AMD/wYahdeUqah0VPsvi17SpV04Kqnt/9u3kPyrylUIV3bnsr+L9DQelSrp0sOzP2SeX6mpu+/wDY8J/jL/4J6VKuHANsL6/7v61oWwf2Cfvf9xpUqhAhSpUqhBUG3i9rC/8AMn/+fEUqVDLo6jpqewnGlSqhdlj6Kx8r39hT/mYP+8U38nv9lP8Aiv8AktKlQ5vmRZj/AOt/cojf2tf+Zb/PVuipUqt0fyFHxD/sX2R//9k=" alt="" class="w-10 rounded-full ">
          </div>
          <!--username-->
          <div class="flex">
            <p class="text-base font-bold ml-2">Vegeto</p>
            <p class="text-xs text-gray-500 ml-2">@imnotgokuandnotvegeta . 7h</p>
          </div>
        </div>

        <!--écris ton tweet-->
        <div>
          <p class="ml-10">When I was 10 when I chattes and saw my name written on the board </p>
        </div>

        <!--photo du post-->
        <div class="mb-2">
          <img src="https://electroallergique.files.wordpress.com/2012/08/are-you-serious1.jpg" class="ml-10 w-10/12">
        </div>

        <!--options-->
        <div class="flex text-gray-500 justify-around">
          <div class="flex">
            <i class="far fa-comment"></i>
            <p class="ml-2 text-xs">130k</p>
          </div>

          <div class="flex">
            <i class="fas fa-sync-alt"></i>
            <p class="ml-2 text-xs">50k</p>
          </div>

          <div class="flex">
            <i class="far fa-heart"></i>
            <p class="ml-2 text-xs">200k</p>
          </div>

          <div class="flex">
            <i class="fas fa-share-alt"></i>
          </div>
        </div>
      </div>
      <!--3ème Post-->
      <div class="text-sm text-white p-2 pb-4">
        <div class="flex">
          <!--PP-->
          <div>
            <img src="https://www.who.int/images/default-source/health-topics/health-financing/novel-coronavirus-ru.jpg?sfvrsn=755458c4_12" alt="" class="w-10 rounded-full ">
          </div>
          <!--username-->
          <div class="flex">
            <p class="text-base font-bold ml-2">Corona</p>
            <p class="text-xs text-gray-500 ml-2">@Corona_le_virus . 01/01/2021</p>
          </div>
        </div>

        <!--écris ton tweet-->
        <div>
          <p class="ml-10">Moi : Quand j'ai vu que les humains ont survécu à 2020</p>
        </div>

        <!--photo du post-->
        <div class="mb-2">
          <img src="https://i.pinimg.com/736x/73/b5/85/73b5858b4ec0a510331d06da45220a5e.jpg" class="ml-10 w-10/12">
        </div>

        <!--options-->
        

        <div class="flex text-gray-500 justify-around">
            <div class="flex">
              <i class="far fa-comment"></i>
              <p class="ml-2 text-xs">3,3M</p>
            </div>
  
            <div class="flex">
              <i class="fas fa-sync-alt"></i>
              <p class="ml-2 text-xs">0</p>
            </div>
  
            <div class="flex">
              <i class="far fa-heart"></i>
              <p class="ml-2 text-xs">0</p>
            </div>
  
            <div class="flex">
              <i class="fas fa-share-alt"></i>
            </div>
          </div>
        </div>



    
</section>


<!--right-->
<section class="hidden lg:block flex-col justify-end w-3/12 h-screen text-white font-bold px-10 border-1 border-grey-200">

    <div class="flex left-0 top-0 mt-5 ml-10 mb-4 text-sm">
        <div class="flex bg-gray-700 w-full m-3 rounded-full pl-2">
          <div class="text-gray-500 text-lg">
            <i class="fas fa-search"></i>
          </div>
          <input type="Text" class= bg-transparent />
           
        </div>
      </div>

    

</div>
<div class="flex flex-col bg-gray-700 rounded-lg mb-6  "> Trends for you<br>
    <div class="p-3 border-b border-t"><a href="#" class="hover:underline">#Dragonballlegends</a><br></div>
    <div class="p-3 border-b"><a href="#" class="hover:underline">#DragonBallHeroes</a><br></div>
    <div class="p-3 border-b"><a href="#" class="hover:underline">#DragonBallsuper</a><br></div>
    <div class="p-3 border-b"><a href="#" class="hover:underline">#DragonBallZ</a><br></div>
    <div class="p-3 "><a href="#" class="hover:underline">show more...</a></div>
  </div>

 <div class="flex flex-col bg-gray-700 rounded-lg mb-6 ">Who to follow <br>
 <div class="p-3 border-b border-t"><a href="#" class="hover:underline">Son goku</a>
    <br><div class="text-sm ml-2 text-gray-600">@goku4real</div></div>   
 <div class="p-3 border-b border-t"><a href="#" class="hover:underline">Vegeta</a>
    <br><div class="text-sm ml-2 text-gray-600">@vegeta4real</div></div>   
 <div class="p-3 border-b border-t"><a href="#" class="hover:underline">Son Gohan</a>
    <br><div class="text-sm ml-2 text-gray-600">@gohan4real</div></div>   
 <div class="p-3 "><a href="#" class="hover:underline">show more...</a></div>

</div>



    
</section>


</body>
</html> 

```
## Author  
* Name: KONE BAKARY
* Github: [bakarykone](https://github.com/bakarykone)


## Request
I know this is not a perfect replica of Twitter but i'm very pround to share with all of you.


# Ex08 Event Registration Web Application
## Date:19.12.2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
home page 1
import React from "react";
import DANCE11 from "./DANCE-1-1.png";
import SEC21 from "./SEC-2-1.png";
import download1Sec2 from "./download-1-SEC-2.png";

export const IphonePlus = () => {
  return (
    <div className="bg-white w-full min-w-[428px] min-h-[926px] relative">
      <img
        className="absolute top-[17px] left-3 w-[404px] h-[84px] aspect-[4.97]"
        alt="Sec"
        src={SEC21}
      />

      <img
        className="absolute top-[101px] left-[104px] w-[220px] h-[215px] aspect-[1.02] object-cover"
        alt="Download SEC"
        src={download1Sec2}
      />

      <div className="top-[327px] left-[41px] w-[346px] h-[89px] bg-[#bfcef2] absolute flex">
        <div className="mt-[27px] w-[264px] h-[49px] ml-[60px] [font-family:'Holtwood_One_SC-Regular',Helvetica] font-normal text-black text-3xl tracking-[0] leading-[normal]">
          DANCE EVENT
        </div>
      </div>

      <div className="top-[439px] left-[135px] w-[175px] h-[60px] bg-[#18ffe4] overflow-hidden absolute flex">
        <div className="mt-[13px] w-[118px] h-[49px] ml-[18px] [font-family:'Holtwood_One_SC-Regular',Helvetica] font-normal text-black text-3xl tracking-[0] leading-[normal]">
          LOGIN
        </div>
      </div>

      <div className="top-[538px] left-[104px] w-60 h-[57px] bg-[#d6f0f1] overflow-hidden absolute flex">
        <div className="mt-3.5 w-[181px] h-[49px] ml-4 [font-family:'Holtwood_One_SC-Regular',Helvetica] font-normal text-black text-3xl tracking-[0] leading-[normal]">
          REGISTER
        </div>
      </div>

      <img
        className="absolute top-[355px] left-0 w-[416px] h-[571px] aspect-[0.75]"
        alt="Dance"
        src={DANCE11}
      />
    </div>
  );
};
```
```
page 2
import React from "react";
import DANCE21 from "./DANCE-2-1.png";
import star3 from "./star-3.svg";
import star4 from "./star-4.svg";
import star5 from "./star-5.svg";
import star6 from "./star-6.svg";
import star7 from "./star-7.svg";
import star8 from "./star-8.svg";
import star9 from "./star-9.svg";

export const IphonePlus = () => {
  return (
    <div className="bg-white w-full min-w-[428px] min-h-[926px] relative">
      <div className="absolute top-0 left-0 w-[428px] h-[83px] flex bg-[#ed1919]">
        <div className="mt-[17px] w-[285px] h-[49px] ml-[71px] [font-family:'Holtwood_One_SC-Regular',Helvetica] text-white text-3xl font-normal tracking-[0] leading-[normal]">
          DANCE EVENTS
        </div>
      </div>

      <img
        className="absolute top-[312px] left-[66px] w-[52px] h-[43px]"
        alt="Star"
        src={star3}
      />

      <img
        className="absolute top-[397px] left-[67px] w-[52px] h-[43px]"
        alt="Star"
        src={star4}
      />

      <img
        className="absolute top-[483px] left-[68px] w-[49px] h-[43px]"
        alt="Star"
        src={star5}
      />

      <img
        className="absolute top-[164px] left-[85px] w-2 h-px"
        alt="Star"
        src={star6}
      />

      <img
        className="absolute top-[143px] left-[72px] w-11 h-10"
        alt="Star"
        src={star7}
      />

      <div className="absolute top-[148px] left-[131px] [font-family:'Grechen_Fuemen-Regular',Helvetica] text-black text-xl whitespace-nowrap font-normal tracking-[0] leading-[normal]">
        DANCE WORKSHOP
      </div>

      <img
        className="absolute top-[243px] left-[94px] w-px h-3"
        alt="Star"
        src={star8}
      />

      <img
        className="absolute top-[226px] left-[75px] w-10 h-[43px]"
        alt="Star"
        src={star9}
      />

      <div className="absolute top-[233px] left-[131px] [font-family:'Grechen_Fuemen-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal] whitespace-nowrap">
        STREET DANCE BATTLE
      </div>

      <div className="absolute top-[319px] left-[159px] [font-family:'Grechen_Fuemen-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal] whitespace-nowrap">
        FLASH MOB
      </div>

      <div className="absolute top-[400px] left-[136px] [font-family:'Grechen_Fuemen-Regular',Helvetica] text-black text-xl whitespace-nowrap font-normal tracking-[0] leading-[normal]">
        DANCE MARATHON
      </div>

      <div className="absolute top-[492px] left-[141px] [font-family:'Grechen_Fuemen-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal] whitespace-nowrap">
        CULTURAL DANCE
      </div>

      <img
        className="absolute top-[516px] left-[141px] w-[266px] h-[374px] aspect-[0.71]"
        alt="Dance"
        src={DANCE21}
      />
    </div>
  );
};
```
```
page 3
import React from "react";
import DANCE31 from "./DANCE-3-1.png";

export const IphonePlus = () => {
  return (
    <div className="bg-white w-full min-w-[428px] min-h-[926px] relative">
      <div className="absolute top-0 left-0 w-[428px] h-[82px] bg-[#9479b9]" />

      <div className="absolute top-[149px] left-[60px] w-0.5 h-[5px] bg-[#d9d9d9]" />

      <div className="absolute top-[129px] left-6 w-[190px] h-[63px] bg-[#d9d9d9] rounded-[40px]" />

      <div className="absolute top-64 left-[62px] w-px h-1 bg-[#d9d9d9]" />

      <div className="absolute top-[319px] left-[42px] w-[175px] h-[58px] bg-[#d9d9d9] rounded-[40px]" />

      <div className="absolute top-[424px] left-[41px] w-[178px] h-14 bg-[#d9d9d9] rounded-[40px]" />

      <div className="absolute top-[527px] left-[52px] w-[165px] h-12 bg-[#d9d9d9] rounded-[40px]" />

      <div className="absolute top-36 left-[84px] [font-family:'Homemade_Apple-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        name
      </div>

      <div className="absolute top-[225px] left-[42px] w-[164px] h-[61px] bg-[#d9d9d9] rounded-[40px]" />

      <div className="absolute top-[230px] left-[97px] [font-family:'Homemade_Apple-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        gender
      </div>

      <div className="absolute top-[326px] left-[105px] [font-family:'Homemade_Apple-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        age
      </div>

      <div className="absolute top-[430px] left-[74px] [font-family:'Homemade_Apple-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        register no
      </div>

      <div className="absolute top-[532px] left-[83px] [font-family:'Homemade_Apple-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        mobile no
      </div>

      <div className="absolute top-[646px] left-[83px] w-px h-0.5 bg-[#d9d9d9]" />

      <div className="absolute top-[614px] left-6 w-[248px] h-[68px] bg-[#d9d9d9] rounded-[40px] rotate-[0.69deg]" />

      <div className="absolute top-[627px] left-[43px] [font-family:'Homemade_Apple-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        events&nbsp;&nbsp;registered
      </div>

      <div className="absolute top-[746px] left-[104px] w-[203px] h-[61px] bg-[#e11212]" />

      <div className="absolute top-[763px] left-[149px] [font-family:'Holtwood_One_SC-Regular',Helvetica] font-normal text-white text-xl tracking-[0] leading-[normal]">
        SUBMIT
      </div>

      <img
        className="absolute top-[149px] left-[214px] w-[214px] h-[231px] aspect-[1.26] object-cover"
        alt="Dance"
        src={DANCE31}
      />

      <div className="absolute top-[26px] left-[30px] [font-family:'Holtwood_One_SC-Regular',Helvetica] font-normal text-white text-xl tracking-[0] leading-[normal]">
        EVENT REGISTRATION FORUM
      </div>
    </div>
  );
};
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 191442-1.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.

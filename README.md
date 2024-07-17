# Business Blog Card

This Project is Portfolio and Experience.

![alt text](image.png)

## Scripts Coding

#### Javascript Scripts

```js
// Import React
import React from "react";
// Import CSS
import "./business-blog-card.css";

function Business() {
    return(
        // Main Container
        <div className="main-container">
            {/* Box Container */}
            <div className="container-image">
                {/* Box Image */}
                <img src="https://github.com/WaelBenseghir/Practice-git/blob/Practice/hero-image-business-card.png?raw=true" alt="image1" className="image-box"></img>
                <svg className="svg-image" viewBox="0 0 418 63" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M0 29.2723C49.8111 33.1558 142.803 32.8672 173.912 28.8749C195.536 26.0997 215.146 21.9909 234.225 17.9931C243.347 16.0818 252.413 13.6909 261.547 11.2823C282.757 5.6889 304.329 0 327.8 0C349.718 0 369.892 9.71262 388.837 18.8332C394.823 21.7151 400.687 24.5379 406.444 26.9765L406.452 26.9802L406.458 26.9827C410.375 28.6417 414.222 30.2715 418 31.8183V67.722H0V29.2723ZM304.713 10.8978C305.217 11.4203 304.096 11.8313 303.176 12.1689L303.163 12.1738C302.851 12.2881 302.668 12.367 302.533 12.4248C302.27 12.5383 302.193 12.5713 301.703 12.6336C301.614 12.645 301.39 12.709 301.174 12.7707C300.972 12.8285 300.777 12.8843 300.706 12.8931C300.332 12.9395 300.051 13.0553 299.804 13.1569C299.651 13.2199 299.512 13.2774 299.371 13.3097C298.465 13.518 297.552 13.6865 296.714 13.8413L296.611 13.8603C295.721 14.0246 294.911 14.176 294.129 14.3606C292.627 14.715 291.114 15.0207 289.646 15.3132L289.196 15.4027C288.57 15.5272 288.04 15.5887 287.52 15.6488C286.942 15.7158 286.377 15.7812 285.709 15.9304C284.87 16.1179 284.191 16.2304 283.523 16.3414C282.763 16.4674 282.016 16.5914 281.058 16.8208C280.818 16.8782 280.245 16.9899 279.673 17.1015L279.672 17.1016C279.105 17.2121 278.538 17.3225 278.299 17.3795C277.3 17.6176 276.436 17.7684 276.105 17.1908C275.878 16.7954 275.95 16.7592 276.351 16.5578C276.536 16.4651 276.79 16.3374 277.117 16.1235C277.35 16.0678 277.907 15.8865 278.463 15.7052C279.018 15.5241 279.574 15.343 279.81 15.2866C280.655 15.0841 281.27 14.8999 281.872 14.7191L281.872 14.719C282.557 14.5135 283.228 14.3124 284.207 14.0937C285.549 13.7939 286.904 13.5246 288.217 13.2634L288.217 13.2633L288.669 13.1734C290.137 12.8809 291.556 12.5936 292.943 12.2661C293.892 12.0423 294.845 11.8655 295.719 11.7041L295.773 11.6943C296.205 11.6144 296.459 11.6286 296.697 11.642C296.942 11.6557 297.172 11.6686 297.563 11.5785C297.83 11.5171 298.205 11.4122 298.603 11.3013C299.263 11.1169 299.983 10.9155 300.368 10.8686L300.455 10.858C300.541 10.8475 300.622 10.8374 300.698 10.8278C301.464 10.7303 301.88 10.6507 302.126 10.5602C303.049 10.2217 304.207 10.3728 304.713 10.8978ZM16.1592 34.1874C16.6926 34.115 17.342 34.0268 17.2485 33.5155C17.1545 33.0017 16.6448 32.644 16.1099 32.7166C15.9668 32.7361 15.7464 32.712 15.3539 32.6293C15.3023 32.6184 15.2459 32.606 15.1857 32.5928L15.1852 32.5927C14.9885 32.5496 14.5884 32.5571 14.2219 32.5641C14.0015 32.5683 13.7932 32.5722 13.6487 32.5648C13.4367 32.5538 13.3309 32.4962 13.218 32.4349C13.1079 32.375 12.9911 32.3114 12.7624 32.284L12.7343 32.2807C12.2724 32.2254 11.7683 32.1656 11.2531 32.1435C10.4996 32.1112 9.74266 32.0412 8.96067 31.9649L8.7202 31.9414C8.02079 31.8729 7.29944 31.8022 6.5753 31.7577C6.04695 31.7252 5.67093 31.743 5.28674 31.7612C4.94861 31.7772 4.60415 31.7935 4.14393 31.7761C4.01586 31.7713 3.70012 31.7973 3.38453 31.8232C3.06837 31.8493 2.75236 31.8753 2.62534 31.8703C2.40949 31.9692 2.25245 32.016 2.13846 32.05C1.89085 32.1239 1.84636 32.1372 1.84347 32.4922C1.83925 33.0107 2.29369 33.0723 2.83671 33.0937C2.9669 33.0988 3.26797 33.1302 3.56954 33.1616C3.87373 33.1932 4.17841 33.225 4.30874 33.2299C4.82981 33.2496 5.22098 33.3078 5.61834 33.3669C5.96839 33.419 6.32324 33.4718 6.77593 33.4996C7.13647 33.5218 7.42413 33.5878 7.71869 33.6555C7.9832 33.7162 8.25327 33.7782 8.58667 33.8109L8.82622 33.8343C9.60817 33.9105 10.4152 33.9857 11.2307 34.0207C11.6555 34.039 12.0842 34.0888 12.5545 34.1451L12.6088 34.1516C13.0521 34.2047 13.5348 34.2626 14.025 34.2879C14.101 34.2918 14.1837 34.2759 14.2742 34.2586C14.4204 34.2305 14.5869 34.1985 14.7782 34.2399C14.8148 34.2478 14.9235 34.2447 15.036 34.2416C15.1562 34.2382 15.2808 34.2347 15.3265 34.2443C15.5775 34.2972 15.6234 34.2874 15.781 34.2536C15.8614 34.2364 15.9708 34.213 16.1515 34.1884L16.1592 34.1874Z"
                        fill="white" />
                </svg>
            </div>

            {/* Container Topic */}
            <div className="container-topic">
                {/* Text Topic */}
                <h4 className="txt-perfect">Perfect solution for small business</h4>
            </div>

            {/* Container Description */}
            <div className="container-small">
                {/* Text Description */}
                <p className="txt-small">Small businesses need to generate leads to grow. You can use tools like Ringy.</p>
            </div>

            <hr className="container-hr" color="#F8F9F9"></hr>
            
            {/* Image Account Container */}
            <div className="container-account">
                {/* Box Container */}
                <div className="container-image-account">
                    {/* Image Account */}
                    <img src="https://github.com/WaelBenseghir/Practice-git/blob/Practice/avatar-image-business-card.png?raw=true" alt="image-account" className="image-accounts"></img>
                </div>
                
                {/* Name and Position Container */}
                <div className="container-name-position">
                    {/* Name Container */}
                    <p className="txt-amy">Amy Burgess</p>
                    {/* Position Container */}
                    <p className="txt-customer">Customer Manger, Solution Oy</p>
                </div>
            </div>
        </div>
    )
};

export default Business;
```

#### CSS Scripts

```css
/* Import Fonts Form Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');

* {
    margin: 0 auto;
    padding: 0 auto;
    box-sizing: border-box;
    font-family: "Lato", sans-serif;
}

html {
    display: flex;
    flex-direction: column;
}

body {
    background-color: #F2F5F9;
}

/* Main Container */
div.main-container {
    border: #FFFFFF 1px solid;
    border-radius: 10px;
    background-color: #FFFFFF;
    margin-top: 124px;
    width: 420px;
    max-width: 420px;
    height: auto;

    /* Box Container */
    & div.container-image {
        position: relative;
        display: inline-block;
        border-radius: 10px;

        /* Box Image */
        & img.image-box {
            display: block;
            height: 280px;
            border-radius: 10px;
        }

        & svg.svg-image {
            position: absolute;
            bottom: 0px;
        }
    }

    /* Container Topic */
    & div.container-topic {
        display: block;
        padding: 0 32px 0 32px;

        /* Text Topic */
        & h4.txt-perfect {
            font-size: 24px;
            font-style: normal;
            font-optical-sizing: auto;
            color: #111729;
        }
    }

    /* Container Description */
    & div.container-small {
        margin-top: 12px;
        margin-left: 32px;
        margin-right: 32px;
        margin-bottom: 24px;

        /* Text Description */
        & p.txt-small {
            font-size: 16px;
            color: #677489;
        }
    }

    & hr.container-hr {
        opacity: 0.5;
    }

    /* Image Account Container */
    & div.container-account {
        border: none;
        height: 42px;
        margin-top: 24px;
        margin-left: 32px;
        margin-right: 32px;
        margin-bottom: 24px;

        /* Box Container */
        & div.container-image-account {
            border: none;
            width: 40px;
            height: 40px;
            float: left;
            border-radius: 50%;
            display: block;

            /* Image Account */
            & img.image-accounts {
                width: 100%;
                border-radius: 50%;
            }
        }

        /* Name and Position Container */
        & div.container-name-position {
            border: none;
            margin-left: 52px;
            height: 40px;

            /* Name Container */
            & p.txt-amy {
                padding-top: 1px;
                font-size: 16px;
                font-weight: bold;
                color: #111729;
            }

            /* Position Container */
            & p.txt-customer {
                padding-top: 1px;
                font-size: 12.5px;
                color: #677489;
                font-style: normal;
            }
        }
    }
}
```

Run Project on Terminal

### `npm start`

## Result

![alt text](image-1.png)

![alt text](image-2.png)

![alt text](image-3.png)
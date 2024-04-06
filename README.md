## Description
sf-react-range-cal is a lightweight and highly customizable React component library that provides a simple yet powerful mobile responsive date range selection feature for your web applications. No More Aditional packages required. built with pure css and react.

## Demo
...

## Features
-React Based Rate range picker
-Competible with tailwind css
-Flexible Positioning using props
-Easily get start and date range
...
## Installation
You can install this package via npm: 
npm i sf-react-range-cal

## bash
npm i sf-react-range-cal
Usage
```js
// Example usage
import React from 'react'
import RangeCalender from '@/components/CommonCalendar'

type Props = {}

const page = (props: Props) => {

  const handlelog = (start:string | null, end:string | null) => {
    console.log(start, end);
    
  }
  return (
   <div className='flex justify-center'>
     <div className=''>
      <RangeCalender
      position='bottom-center'
    handleApply={handlelog}
    ></RangeCalender>
    </div>
   </div>
  )
}

export default page
```
## someFunction()
-React Based Rate range picker
-Competible with tailwind css
-Flexible Positioning using props
-More is comming...


Any contributions you make are greatly appreciated. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Support
For support, contact codersaki98@gmail.com.# sf-react-range-cal

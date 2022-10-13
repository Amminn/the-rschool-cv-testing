# Benkhaled Amin

## Front-end web developer 

### Contact

- **Portfolio:** [https://amminn.github.io/Portfolio/](https://amminn.github.io/Portfolio/ "https://amminn.github.io/Portfolio/")
- **linkedin:** [amin-benkhaled](https://www.linkedin.com/in/amin-benkhaled-3140641b5/ "amin-benkhaled")
- **E-mail:** benkha1ed.amn@gmail.com
- **Discord:** Amin#4046

------------

### Briefly About Myself:
Web developer started in college as a full-stack/multimedia web developer then specialized more on the Front end by taking the Scrimba career path.

Skilled in problem-solving with React, JavaScript, SCSS/CSS, WordPress, MySQL, and PHP Also UI/UX side with Adobe programs and Figma.

I enjoy helping others and am fully motivated to progress and expand my skill set, by getting more real projects to gain more experience in the field.

------------

### Skills and Proficiency:
- HTML5, CSS3, SCSS
- JavaScript
- React
- Git, GitHub
- PHP, MySQL, PHPMyAdmin
- UI/UX, Adobe programs, Figma

------------

### Code example:
```js
import React from 'react'
import {Context} from '../Context'
function Favorite() {
  const {favoriteMeal, selectMeal, removeFavorite} = React.useContext(Context)
  const renderFavoriteMeals = favoriteMeal.map(item => {
    const {idMeal, strMeal: title, strMealThumb: img} = item
    return (
		<div key={idMeal} id={idMeal} className="favorite-item">
		<img className='favorites-img' src={img} alt={`${title} image`} onClick={() => selectMeal(idMeal)} />
		<p className="remove-btn" onClick={() => removeFavorite(idMeal)}>remove</p>
		</div>
    )
  }) 
  return (
    <section className='favorites'>
      <div className="favorites-content">
          <h2>Favorites</h2>
        <div className="favorites-container">
          {renderFavoriteMeals}
        </div>
      </div>
    </section>
  )
}
export default Favorite
```
This code simple is a component called *Favorite*, and it is from this project: [Meals Application](https://amminn.github.io/meals-application/ "meals application")
You can use this application to see some delicious yummy meals, You can look for more using the search bar and check the ingredients, besides saving your favorite meals so you can return back to them later.

#### Some other Projects:
- [Trading-King](https://amminn.github.io/trading-king/ "Trading-King")
- [PayAPI](https://amminn.github.io/payapi/ "PayAPI")
- [Tenzies-Project](https://amminn.github.io/Tenzies-Project/ "Tenzies-Project")

------------

### Courses / Certeficates:
- RS School. JS/Frontend development course (in progress)
- The Frontend Developer Career Path from [Scrimba](https://scrimba.com/ "Scrimba") ([certificate](https://scrimba.com/certificate/u6WER6Tr/gfrontend "certificate"))
- Bachelor's degree, Full Stack Web developer / Multimedia  (graduated)

------------
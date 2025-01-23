
## **Recipe API Endpoints**

### **1. Search Recipes by title** - (Implemented)
- **Endpoint:** `GET api/recipe-bytitle/recipeByTitle`
- **Query Parameters:**
  - `title` (string, required): Recipe name or title.
- **Description:** Search for recipes by name/title . The `recipetitle` parameter is used to search for recipes that match the name.
- **Example Request:**
  ```
  GET /api/recipe-bytitle/recipeByTitle?title=Dukkah)
  ```
- **Example Response:**
  ```json
 
    "success": true,
    "message": "Recipes fetched successfully.",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890d6d",
            "Recipe_id": "2614",
            "Calories": "45.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "24",
            "Recipe_title": "Dukkah",
            "total_time": "25",
            "Region": "Middle Eastern",
            "Continent": "African"
        },
        {
            "_id": "64057243a13d0d2d35894c9e",
            "Recipe_id": "47216",
            "Calories": "96.9",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Dukkah",
            "total_time": "10",
            "Region": "Middle Eastern",
            "Continent": "African"
        },
        {
            "_id": "64057243a13d0d2d35894ca2",
            "Recipe_id": "47220",
            "Calories": "341.6",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4 eggs",
            "Recipe_title": "Egyptian Eggs With Dukkah",
            "total_time": "15",
            "Region": "Middle Eastern",
            "Continent": "African"
        },
        {
            "_id": "64057243a13d0d2d35894cee",
            "Recipe_id": "47296",
            "Calories": "141.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "1 dip",
            "Recipe_title": "Cousin Pete's Yummiest Dukkah (Nut Dip)",
            "total_time": "25",
            "Region": "Middle Eastern",
            "Continent": "African"
        },
        {
            "_id": "64057243a13d0d2d35894cf7",
            "Recipe_id": "47305",
            "Calories": "260.5",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Chargrilled Vegetable and Pita Salad With Feta and Dukkah",
            "total_time": "20",
            "Region": "Middle Eastern",
            "Continent": "African"
        },
        {
            "_id": "64057243a13d0d2d35894d2f",
            "Recipe_id": "47361",
            "Calories": "1007.7",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "2 cups",
            "Recipe_title": "Dukkah",
            "total_time": "20",
            "Region": "Middle Eastern",
            "Continent": "African"
        },
        {
            "_id": "64057245a13d0d2d35895308",
            "Recipe_id": "48859",
            "Calories": "188.2",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "16 balls",
            "Recipe_title": "Labna Balls Rolled in Tunisian Dukkah",
            "total_time": "1470",
            "Region": "Rest Africa",
            "Continent": "African"
        },
        {
            "_id": "64057245a13d0d2d358953b2",
            "Recipe_id": "49029",
            "Calories": "790.2",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "3/4 cup",
            "Recipe_title": "Almond Dukkah",
            "total_time": "22",
            "Region": "Rest Africa",
            "Continent": "African"
        },
        {
            "_id": "6405724aa13d0d2d358957b1",
            "Recipe_id": "50053",
            "Calories": "196.1",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "6",
            "Recipe_title": "Brie With Dukkah",
            "total_time": "20",
            "Region": "Northern Africa",
            "Continent": "African"
        },
        {
            "_id": "6405725ea13d0d2d35897f3d",
            "Recipe_id": "60187",
            "Calories": "277.5",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "6",
            "Recipe_title": "Dukkah",
            "total_time": "30",
            "Region": "Middle Eastern",
            "Continent": "Asian"
        },
        {
            "_id": "64057262a13d0d2d3589840c",
            "Recipe_id": "61418",
            "Calories": "103.2",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4 1/2 pint jars",
            "Recipe_title": "Darcey's Special Dukkah",
            "total_time": "20",
            "Region": "Middle Eastern",
            "Continent": "Asian"
        },
        {
            "_id": "64057262a13d0d2d3589855c",
            "Recipe_id": "61754",
            "Calories": "76.9",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "24 skewers",
            "Recipe_title": "Chicken Skewers With Dukkah Crust and Balsamic Reduction",
            "total_time": "60",
            "Region": "Middle Eastern",
            "Continent": "Asian"
        },
        {
            "_id": "64057277a13d0d2d3589a553",
            "Recipe_id": "69938",
            "Calories": "2866.2",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "1 jar",
            "Recipe_title": "Dukkah",
            "total_time": "60",
            "Region": "Middle Eastern",
            "Continent": "Asian"
        },
        {
            "_id": "6405727da13d0d2d3589ae5c",
            "Recipe_id": "72252",
            "Calories": "218.3",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "3 cups",
            "Recipe_title": "Dukkah (Spicy Nut Mix for Dipping With Flatbread)",
            "total_time": "35",
            "Region": "Indian Subcontinent",
            "Continent": "Asian"
        },
        {
            "_id": "6405727da13d0d2d3589b020",
            "Recipe_id": "72704",
            "Calories": "239.4",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "8",
            "Recipe_title": "Prawns With Chilli Mayo & Pistachio Dukkah",
            "total_time": "20",
            "Region": "Australian",
            "Continent": "Australasian"
        },
        {
            "_id": "6405727fa13d0d2d3589b559",
            "Recipe_id": "74043",
            "Calories": "5545.7",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "1 loaf",
            "Recipe_title": "Garlic  Dukkah  Bread",
            "total_time": "40",
            "Region": "Australian",
            "Continent": "Australasian"
        },
        {
            "_id": "64057286a13d0d2d3589bf35",
            "Recipe_id": "76569",
            "Calories": "346.9",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "6",
            "Recipe_title": "Dukkah Crusted Lamb, Apricot Salsa, Herb Salad With Chermoula D",
            "total_time": "40",
            "Region": "Australian",
            "Continent": "Australasian"
        },
        {
            "_id": "64057288a13d0d2d3589c355",
            "Recipe_id": "77625",
            "Calories": "260.6",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Dukkah Spiced Carrot & Feta Salad",
            "total_time": "40",
            "Region": "Australian",
            "Continent": "Australasian"
        }
    ]


  ```
- **Error Handling:**
  - If `recipeName` is not provided:
    ```json
    {
       "success": false,
       "message": "Recipe title is required."
    }
  - If no recipes match the search criteria:
    ```json
    {
      "message": "No recipes found"
    }
    ```
  - Internal server errors:
    ```json
    {
      "message": "Internal Server Error"
    }
    ```
- **Response time**:
  `300 ms `
  
---
### 2. Get Recipe of Day- (Implemented)

**Endpoint**: `GET /recipe/recipeofday`

**Parameters**:  
- None.

**Description**: Fetch the detail of any recipe from the Database and list it,changes the recipe when the date changes.

**Sample Request**:  
`GET /recipe/recipeofday`

**Example Response**:
```json
{
   "success": "true",
    "message": "Recipe fetched successfully.",
    "payload": {
        "data": {
            "_id": "640572b7a13d0d2d3589fb04",
            "Recipe_id": "91897",
            "Calories": "2710.2",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "1 loaf",
            "Recipe_title": "Apricot Banana Bread",
            "total_time": "72",
            "url": "http://www.geniuskitchen.com/recipe/apricot-banana-bread-27313",
            "Region": "Caribbean",
            "Sub_region": "Rest Caribbean",
            "Continent": "Latin American",
            "Source": "Geniuskitchen",
            "img_url": "https://img.sndimg.com/food/image/upload/w_555,h_416,c_fit,fl_progressive,q_95/v1/img/recipes/27/31/3/picWWB1AP.jpg",
            "Carbohydrate, by difference (g)": "426.4682",
            "Energy (kcal)": "3272.378",
            "Protein (g)": "47.1232",
            "Total lipid (fat) (g)": "161.8544",
            "Utensils": "pan||pan",
            "Processes": "cream||add||mix||mix||add||stir||pour||bake||cool",
            "vegan": "0.0",
            "pescetarian": "0.0",
            "ovo_vegetarian": "0.0",
            "lacto_vegetarian": "0.0",
            "ovo_lacto_vegetarian": "0.0"
        }
    }
}
```
- **Response time**:
  `48 ms `
---

### 3. Get Recipe by Time range - (Implemented)

**Endpoint**: `GET /api/recipes/range`

**Parameters**:  
- `min` (integer,required): Minimum time.
- `max` (integer,required): Maximum time.
- `field` (string, required): Which time (total_time,cook_time,prep_time).
- `page` (integer, optional,default=1): Page number.
- `limit` (integer, optional,default=10): Number of instances.

**Description**: Fetch the recipe details filtered by the specific time range.

**Sample Request**:  
`GET /api/recipes/range?min=15&max=60&field=total_time&page=10&limit=10`

**Example Response**:
```json
 "success": true,
    "page": 10,
    "totalPages": 6782,
    "totalResults": 67816,
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e4b",
            "Recipe_id": "2836",
            "cook_time": "32",
            "prep_time": "0",
            "Recipe_title": "Tikil Gomen (Ethiopian Cabbage)",
            "total_time": 32,
            "Region": "Rest Africa",
            "Sub_region": "Nigerian",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e4c",
            "Recipe_id": "2837",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Iranian _ Persian Salad Shirazi",
            "total_time": 20,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e4e",
            "Recipe_id": "2839",
            "cook_time": "35",
            "prep_time": "20",
            "Recipe_title": "Lamb and Asparagus Stew",
            "total_time": 55,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e50",
            "Recipe_id": "2841",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Persian-Style Tomato Avocado Salad",
            "total_time": 20,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e51",
            "Recipe_id": "2842",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Shiraz Salad",
            "total_time": 20,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e53",
            "Recipe_id": "2844",
            "cook_time": "30",
            "prep_time": "15",
            "Recipe_title": "Persian Fesenjun",
            "total_time": 45,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e60",
            "Recipe_id": "2857",
            "cook_time": "0",
            "prep_time": "15",
            "Recipe_title": "Jarjeer (Arugula) Salad",
            "total_time": 15,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e62",
            "Recipe_id": "2859",
            "cook_time": "16",
            "prep_time": "10",
            "Recipe_title": "Wheat Flour Halva",
            "total_time": 46,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e63",
            "Recipe_id": "2860",
            "cook_time": "35",
            "prep_time": "10",
            "Recipe_title": "Eggplant Mirza",
            "total_time": 60,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        },
        {
            "_id": "6405721fa13d0d2d35890e64",
            "Recipe_id": "2861",
            "cook_time": "15",
            "prep_time": "15",
            "Recipe_title": "Iskender Kebab",
            "total_time": 30,
            "Region": "Middle Eastern",
            "Sub_region": "Rest Middle Eastern",
            "Source": "AllRecipes"
        }
    ]
```
- **Response time**: 
   `440 ms`
---

### **4. Get Recipe by Calories Range**(Implemented)

- **Endpoint:** `GET /api/recipes-calories/calories`

- **Query Parameters:**
  - **minCalories** (integer, required): The minimum number of calories.
  - **maxCalories** (integer, required): The maximum number of calories.
  - **page** (integer, optional): Specifies the page number for pagination (default is 1).
  - **limit** (integer, optional): Specifies the number of recipes to return per page (default is 10).

**Sample Request**:  
`GET /api/recipes-calories/calories?minCalories=10&maxCalories=30&limit=10`

**Example Response:**
  ```json
  "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890d8c",
            "Calories": "10.0",
            "cook_time": "8",
            "prep_time": "5",
            "Recipe_title": "Guinean Okra Sauce",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/images/79591.png"
        },
        {
            "_id": "6405721fa13d0d2d35890d8e",
            "Calories": "14.0",
            "cook_time": "20",
            "prep_time": "10",
            "Recipe_title": "Best Hot Sauce",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2513802.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890e03",
            "Calories": "10.0",
            "cook_time": "0",
            "prep_time": "40",
            "Recipe_title": "Tunisian Harissa",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/651700.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890e2d",
            "Calories": "28.0",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Harissa",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/776212.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890e40",
            "Calories": "25.0",
            "cook_time": "0",
            "prep_time": "10",
            "Recipe_title": "Berbere (Ethiopian Spice)",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2376305.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ec9",
            "Calories": "25.0",
            "cook_time": "10",
            "prep_time": "120",
            "Recipe_title": "Wontons for Wonton Noodle Soup",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/409196.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ecd",
            "Calories": "26.0",
            "cook_time": "0",
            "prep_time": "0",
            "Recipe_title": "Egg Drop Soup II",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2918090.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890edf",
            "Calories": "28.0",
            "cook_time": "50",
            "prep_time": "50",
            "Recipe_title": "Chinese Steamed Buns with BBQ Pork Filling",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/31733.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ee6",
            "Calories": "22.0",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Overnight Chinese Daikon Radish Pickles",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/199612.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ef0",
            "Calories": "16.0",
            "cook_time": "0",
            "prep_time": "5",
            "Recipe_title": "Chinese-Style Five Spice Rub",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/855861.jpg"
        }
    ]
  ```

**Error Responses:**
1. **The mincalories is greater than maxcalories:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
        "success": false,
        "message": "minCalories cannot be greater than maxCalories"
     }
     ```


2. **No Recipes Found:**
   - **Status Code:** `200 OK`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```

3. **Internal Server Error:**
   - **Status Code:** `500 Internal Server Error`
   - **Response Body:**
     ```json
     {
       "message": "Internal Server Error"
     }
     ```
**Response Time**
   `53ms`  
   
### **5. Get Recipe by Carbohydrate Range**(Implemented)

- **Endpoint:** `GET /api/recipe-carbo/recipes-by-carbs`

- **Query Parameters:**
  - **minCarbs** (integer, required): The minimum number of carbs by gram.
  - **maxnCarbs** (integer, required): The maximum number of carbs by gram.
  - **limit** (integer, optional): Specifies the number of recipes to return per page (default is 10).

**Sample Request**:  
`GET /api/recipes-calories/calories?minCalories=10&maxCalories=30&limit=10`

**Example Response:**
  ```json
  "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890d8c",
            "Calories": "10.0",
            "cook_time": "8",
            "prep_time": "5",
            "Recipe_title": "Guinean Okra Sauce",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/images/79591.png"
        },
        {
            "_id": "6405721fa13d0d2d35890d8e",
            "Calories": "14.0",
            "cook_time": "20",
            "prep_time": "10",
            "Recipe_title": "Best Hot Sauce",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2513802.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890e03",
            "Calories": "10.0",
            "cook_time": "0",
            "prep_time": "40",
            "Recipe_title": "Tunisian Harissa",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/651700.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890e2d",
            "Calories": "28.0",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Harissa",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/776212.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890e40",
            "Calories": "25.0",
            "cook_time": "0",
            "prep_time": "10",
            "Recipe_title": "Berbere (Ethiopian Spice)",
            "Region": "Rest Africa",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2376305.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ec9",
            "Calories": "25.0",
            "cook_time": "10",
            "prep_time": "120",
            "Recipe_title": "Wontons for Wonton Noodle Soup",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/409196.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ecd",
            "Calories": "26.0",
            "cook_time": "0",
            "prep_time": "0",
            "Recipe_title": "Egg Drop Soup II",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2918090.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890edf",
            "Calories": "28.0",
            "cook_time": "50",
            "prep_time": "50",
            "Recipe_title": "Chinese Steamed Buns with BBQ Pork Filling",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/31733.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ee6",
            "Calories": "22.0",
            "cook_time": "0",
            "prep_time": "20",
            "Recipe_title": "Overnight Chinese Daikon Radish Pickles",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/199612.jpg"
        },
        {
            "_id": "6405721fa13d0d2d35890ef0",
            "Calories": "16.0",
            "cook_time": "0",
            "prep_time": "5",
            "Recipe_title": "Chinese-Style Five Spice Rub",
            "Region": "Chinese and Mongolian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/855861.jpg"
        }
    ]
  ```

**Error Responses:**
1. **The mincalories is greater than maxcalories:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
        "success": false,
        "message": "minCalories cannot be greater than maxCalories"
     }
     ```


2. **No Recipes Found:**
   - **Status Code:** `200 OK`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```

3. **Internal Server Error:**
   - **Status Code:** `500 Internal Server Error`
   - **Response Body:**
     ```json
     {
       "message": "Internal Server Error"
     }
     ```
**Response Time**
   `53ms`  


### **5. Get Carbon Footprint of All Ingredients in Recipe** - (Implemented)

- **Endpoint:**  
  `GET /api/recipes/ingredient-cf/:id`

- **Parameters:**
  - **id** (integer): Recipe ID.

- **Description:**  
  Fetch the carbon footprint for all ingredients in a recipe.
- **Example Request:**
  `GET /api/recipes/ingredient-cf/2610`
- **Response Example:**

```json
{
  "recipeName": "Egyptian Lentil Soup",
  "ingredients": [
    {
      "ingredient": "black pepper",
      "carbonFootprint": "Data not available"
    },
    {
      "ingredient": "cumin",
      "carbonFootprint": 2.5
    },
    {
      "ingredient": "garlic",
      "carbonFootprint": 0.67
    },
    {
      "ingredient": "sea salt",
      "carbonFootprint": "Data not available"
    },
    {
      "ingredient": "carrot",
      "carbonFootprint": 0.23
    },
    {
      "ingredient": "coriander",
      "carbonFootprint": 0.73
    },
    {
      "ingredient": "red lentil",
      "carbonFootprint": 0.8
    },
    {
      "ingredient": "water",
      "carbonFootprint": 0.49
    },
    {
      "ingredient": "onion",
      "carbonFootprint": 0.24
    },
    {
      "ingredient": "rom tomato",
      "carbonFootprint": 0.48
    }
  ],
  "totalCarbonFootprint": 6.14
}
```
---

#### **Values to Help You Understand Carbon Footprint**

When calculating the carbon footprint of a recipe, it's important to understand the carbon footprint (CFF) values of individual ingredients. Here are some values and guidelines that can help you assess the carbon footprint of various ingredients:

- **Higher Carbon Footprint Ingredients**: These ingredients typically contribute significantly to a recipe’s total carbon footprint. These are usually animal-based products, which require more resources like land, water, and energy to produce:
  - **Beef**: ~60 kg CO₂e per kg
  - **Lamb**: ~30-50 kg CO₂e per kg
  - **Cheese**: ~20-25 kg CO₂e per kg
  - **Butter**: ~20-30 kg CO₂e per kg

- **Medium Carbon Footprint Ingredients**: These ingredients may have a moderate environmental impact due to agricultural practices or the energy involved in their production:
  - **Poultry**: ~10-15 kg CO₂e per kg
  - **Pork**: ~12-15 kg CO₂e per kg
  - **Eggs**: ~4-6 kg CO₂e per dozen
  - **Rice**: ~4-6 kg CO₂e per kg

- **Lower Carbon Footprint Ingredients**: Plant-based ingredients are generally the most sustainable, having lower carbon footprints due to less resource-intensive farming:
  - **Vegetables**: ~0.1-0.5 kg CO₂e per kg
  - **Fruits**: ~0.2-0.4 kg CO₂e per kg
  - **Legumes (Beans, Lentils, etc.)**: ~0.2-0.4 kg CO₂e per kg
  - **Whole Grains (Wheat, Oats, etc.)**: ~0.5-1.0 kg CO₂e per kg

#### **Why This Matters**

- The **carbon footprint** of a food ingredient refers to the amount of greenhouse gases (GHGs) emitted during its production, processing, and transportation.
- **Plant-based ingredients** tend to have lower carbon footprints because they require fewer resources (such as water and energy) and produce less GHGs compared to animal-based foods.
- **Animal-based foods** tend to have higher carbon footprints due to the resource-intensive processes involved in raising livestock, which include feeding, water usage, land for grazing, and transportation of animal products.

By considering the carbon footprint of individual ingredients, you can make more environmentally conscious decisions in your cooking and reduce the overall impact of your meals.

---

### **6. Get Recipe by Carbon Footprint** - (Implemented)
- **Endpoint:** `GET /api/recipes/carbon-footprint-sum`
- **Query Parameters:**
  - `min` (float): Minimum carbon footprint sum. (Optional)
  - `max` (float): Maximum carbon footprint sum. (Optional)
  - `page` (integer): The page number for paginated results. Default is `1`. (Optional)
  - `limit` (integer): The number of recipes to return per page. Default is `10`. (Optional)

- **Description:** Fetches recipes within a specified carbon footprint sum range. The response is paginated to allow better handling of large datasets.

**Example Request**
```http
GET /api/recipes/carbon-footprint-sum?min=10&max=20&page=1&limit=10
```

**Response Format**
```json
{
    "page": 1,
    "limit": 10,
    "totalResults": 35795,
    "totalPages": 3580,
    "recipes": [
        {
            "_id": "677a844cc7688aaee7cf3a5e",
            "Recipe ID": 2613,
            "ingredient_phrase": "['1/2 small onion , minced', '1 1/2 teaspoons olive oil', '1 can garbanzo beans , rinsed and drained', '1/3 cup imitation sour cream', '2 tablespoons cornmeal', '4 cloves garlic , minced', '1 teaspoon ground cumin', '1 teaspoon ground coriander', '1/2 teaspoon salt', '3/4 teaspoon hot sauce']",
            "continent": "African",
            "region": "Middle Eastern",
            "sub_region": "Egyptian",
            "instructions": "['Cook the onions in 1 1/2 teaspoons of olive oil in a skillet over medium heat until soft and translucent. Pulse the garbanzo beans, imitation sour cream, cornmeal, garlic, cumin, coriander, salt, and hot sauce in a food processor until smooth. Transfer to a bowl and stir in the onions.', 'Cover and chill for 30 minutes. Place 1/4 cup cornmeal in a shallow dish. Form the garbanzo bean dough into 6 patties, 1/2 inch thick.', 'Roll the cakes in cornmeal. Heat 2 tablespoons of olive oil in a large skillet over medium heat. Cook the falafel cakes until browned on both sides, about 5 minutes per side.']",
            "Recipe Name": "Magpie's Easy Falafel Cakes",
            "Recipe Ingredient": "['cornmeal', 'cumin', 'sauce', 'garlic', 'coriander', 'garbanzo bean', 'onion', 'cream', 'salt', 'olive oil']",
            "Total Ingredient": 10,
            "Available Ingredients": "['cornmeal', 'cumin', 'garlic', 'coriander', 'garbanzo bean', 'onion', 'cream', 'olive oil']",
            "Available Count": 8,
            "Not Available Ingredients": "['sauce', 'salt']",
            "Not Available Count": 2,
            "Available Percentage": 80,
            "Carbon_footprint_sum": 15.59,
            "Vegetarian_Recipe": 1,
            "Non_Vegetarian_Recipe": 0,
            "Miscellaneous_Recipe": 0
        }
    ]
}
```
**Pagination Metadata:**
  - `page` (integer): The current page number.
  - `limit` (integer): The maximum number of recipes per page.
  - `totalResults` (integer): The total number of recipes matching the query.
  - `totalPages` (integer): The total number of page in the query result.

**Notes**
- **`min`**: Filters the results by the minimum carbon footprint sum value. Only recipes with a carbon footprint sum greater than or equal to this value will be included.
- **`max`**: Filters the results by the maximum carbon footprint sum value. Only recipes with a carbon footprint sum less than or equal to this value will be included.
- If neither `min` nor `max` is provided, then endpoint will return error message.
- Default pagination settings are `page=1` and `limit=10`.
- Ensure the `limit` value does not exceed a reasonable maximum to avoid performance issues.

---

### **7. Get Recipe Ingredients by Carbon Footprint** - (Implemented)
- **Endpoint:** `GET /api/ingredients/carbon-footprint`
- **Query Parameters:**
  - `min` (float): Minimum carbon footprint. (Optional)
  - `max` (float): Maximum carbon footprint. (Optional)
  - `page` (integer): The page number for paginated results. Default is `1`. (Optional)
  - `limit` (integer): The number of recipes to return per page. Default is `10`. (Optional)

**Description:** Fetch ingredients in recipes within a specified carbon footprint range.The response is paginated to allow better handling of large datasets.

**Example Request:**
```http
GET api/ingredients/carbon-footprint?max=0.5&min=0&page=1&limit=10
```

**Response Format:**
```json
{
    "page": 1,
    "limit": 10,
    "totalResults": 1101,
    "totalPages": 111,
    "ingredients": [
        {
            "_id": "677a8497c7688aaee7d10640",
            "RecipeDB Ingredient": "Onion",
            "Category": "Vegetable",
            "Sueatable Ingredient": "Onion",
            "Food Commodity Group": "Crops",
            "Food Commodity Typology": "Vegetable Openfield",
            "Region": "['N Europe', 'Oceania', 'Asia']",
            "Country": "['Sweden', 'Denmark', 'New Zealand', 'UK', 'Japan', 'Australia']",
            "Carbon Footprint": 0.24,
            "Full Reference": "['Cederberg, C., M. Wivstad, P. Bergkvist, B. Mattsson, K. Ivarsson (2005) HÃ¥llbart vÃ¤xtskydd. Analys av olika strategier fÃ¶r att minska riskerna med kemiska vÃ¤xtskyddsmedel, Rapport MAT21. Acessed 14/02/2015 from http://www.vaxteko.nu/html/sll/slu/rapport_mat_21/RMAT05-06/RMAT05-06.PDF', 'Fuentes, C., A. Carlsson-Kanyama, A. Biel, K. BergstroÌ\\x88m, G. Grankvist, G. Lagerberg, C. Fogelberg, H. Shanahan and C. SoleÌ\\x81r (2006). Environmental information in the food supply system FOI-R--1903--SE. Stockholm, FOI â\\x80\\x93 Swedish Defence Research Agency.', 'GonzÃ¡lez, A. D., B. Frostell and A. Carlsson-Kanyama (2011). \"Protein efficiency per unit energy and per unit greenhouse gas emissions: Potential contribution of diet choices to climate change mitigation.\" Food Policy 36(5): 562-570.', 'Saunders, C., A. Barber and G. Taylor (2006). Food Miles â\\x80\\x93 Comparative Energy/Emissions Performance of New Zealandâ\\x80\\x99s Agriculture Industry. Research Report 285. Lincoln, Agribusiness & Economics Research Unit Lincoln University.', 'Yoshikawa, N., K. Amano, K. Shimada. Evaluation of environmental load on fruits and vegetables consumption and its reduction potential, Ritsumeikan University', 'Yoshikawa, N., K. Amano and K. Shimada (2008). Evaluation of Environmental Loads Related to Fruit and Vegetable Consumption Using the Hybrid LCA Method: Japanese Case Study. Life Cycle Assessment VIII September 30-October 2, . Seattle, Washington.', 'Maraseni, T. N., G. Cockfield, J. Maroulis and G. Chen (2010). \"An assessment of greenhouse gas emissions from the Australian vegetables industry.\" Journal of Environmental Science and Health, Part B 45(6): 578-588.', 'Audsley, E., M. Brander, J. Chatterton, D. Murphy-Bokern, C. Webster and A. Williams (2009). How low can we go? An assessment of greenhouse gas emissions from the UK food system and the scope to reduce them by 2050. London, FCRN-WWF. Accessed: 17/02/2015 from: An assessment of greenhouse gas emissions from the UK food system end and the scope to reduce them by 2050 wwf.org.uk/downloads/how_low_report_1.pdf', 'MiljÃ¸styrelsen. MiljÃ¸vurdering af konventionel og Ã¸kologisk avl af grÃ¸ntsager. Arbejdsrapport nr. 5/2006. KÃ¸benhavn: MiljÃ¸styrelsen.\\nIn: GÃ¶ssling, S., B. Garrod, C. Aall, J. Hille, P. Peeters. Food management in tourism: Reducing tourismâ\\x80\\x99s carbon â\\x80\\x98foodprintâ\\x80\\x99, Tourism Manage 32:534-543, 2011.']",
            "Publication Year": "['2005', '2006', '2011', '2009', '2008', '2010', '2006 (2010)']",
            "Source Type": "['Report', 'Journal', 'Conference']"
        },
    ]
}

```
**Pagination Metadata:**
  - `page` (integer): The current page number.
  - `limit` (integer): The maximum number of ingredients per page.
  - `totalResults` (integer): The total number of ingredients matching the query.
  - `totalPages` (integer): The total number of page in the query result.

**Notes**
- **`min`**: Filters the results by the minimum carbon footprint value. Only ingredients with a carbon footprint greater than or equal to this value will be included.
- **`max`**: Filters the results by the maximum carbon footprint value. Only ingredients with a carbon footprint less than or equal to this value will be included.
- If neither `min` nor `max` is provided, then endpoint will return error message.
- Default pagination settings are `page=1` and `limit=10`.
- Ensure the `limit` value does not exceed a reasonable maximum to avoid performance issues.



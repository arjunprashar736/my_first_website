
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
`GET /api/recipe-carbo/recipes-by-carbs?minCarbs=1000&maxCarbs=2000&limit=20`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **The mincarbs is greater than maxcarbs:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
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
   `70ms`  


### **6. Get Recipe by Method**(Implemented)

- **Endpoint:** `GET /api/recipe-method/{method}`

- **Query Parameters:**
  - **method** (string, required): The method of cooking.
  - **page** (integer, optional): Specifies the page number default is 1.

**Sample Request**:  
`GET api/recipes-method/cook?page=2`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `404 Not found`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms`  

### **7. Get Recipe by Utensils**(Implemented)

- **Endpoint:** `GET /api/byutensils/utensils`

- **Query Parameters:**
  - **utensils** (string, required): The Utensil of cooking.
  - **page** (integer, optional): Specifies the limit number default is 10.

**Sample Request**:  
`GET api/byutensils/utensils?utensils=cUP,bowl&limit=30`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `404 Not found`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms`  

### **8. Get Recipe by Flavour**(Implemented)

- **Endpoint:** `GET /api/ingredients/flavor/{flavor}`

- **Query Parameters:**
  - **Flavour** (string, required): The Flavour of cooking.

**Sample Request**:  
`GET /api/ingredients/flavor/Vegetable-Bulb`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `404 Not found`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms`  

### **9. Get Recipe by Instruction**(Implemented)

- **Endpoint:** `GET /api/instructions/{recipe_id}`

- **Query Parameters:**
  - **Recipe_id** (string, required): The Id of the recipe.

**Sample Request**:  
`GET /api/instruction/2611`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `404 Not found`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 
   
### **10. Get Recipe by Diet**(Implemented)

- **Endpoint:** `GET /api/recipe-diet/recipe-diet`

- **Query Parameters:**
  - **diet** (string, required): The diet type of the recipe (e.g vegan).
  - **limit** (integer,optional): The limit of number of responses (by default 10).

**Sample Request**:  
`GET api/recipe-diet/recipe-diet?diet=VegaN&limit=21`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 
**Note**
  - **supports case insensitivity**

### **11. Get Recipe by Diet and region(both)**(Implemented)

- **Endpoint:** `GET /api/recipe/region-diet`

- **Query Parameters:**
  - **diet** (string, required): The diet type of the recipe (e.g vegan).
  - **Region** (string, required): The Region type of the recipe (e.g Middle eastern).
  - **limit** (integer,optional): The limit of number of responses (by default 10).

**Sample Request**:  
`GET api/recipe/region-diet/region-diet?region=South american&diet=vegan&limit=10`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 
**Note**
  - **supports case insensitivity**


### **12. Get Recipe info**(Implemented)

- **Endpoint:** `GET /recipe/recipesinfo`

- **Query Parameters:**
  - **page** (integer, optional): The Page number(by default 1).
  - **limit** (integer, optional): The limit of number of responses (by default 10).

**Sample Request**:  
`GET recipe/recipesinfo?limit=10`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 
   
**Note**
  - **supports case insensitivity**

### **13. Get Recipe Nutrition info**(Implemented)

- **Endpoint:** `GET /recipe-nutri/nutritioninfo`

- **Query Parameters:**
  - **page** (integer, optional): The Page number(by default 1).
  - **limit** (integer, optional): The limit of number of responses (by default 10).

**Sample Request**:  
`GET recipe-nutri//nutritioninfo/?limit=2&page=1`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 
   
### **14. Get Recipe Micro-Nutrition info**(Implemented)

- **Endpoint:** `GET /recipe-micronutri/micronutritioninfo`

- **Query Parameters:**
  - **page** (integer, optional): The Page number(by default 1).
  - **limit** (integer, optional): The limit of number of responses (by default 10).

**Sample Request**:  
`GET recipe-micronutri/micronutritioninfo/?limit=10&&page=1`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 



### **15. Post API meal-plan**(Implemented)

- **Endpoint:** `POST api/meal-plan`

- **Query Body:**
  - **diet_type** (string, required): The Diet type.
  - **calories_per_day** (integer, required): The limit of number of calories.
  -  **days** (integer,required) :The number of days for which you want plan
  -  ```json
     {
      "diet_type": "vegan",
      "calories_per_day": "8000.0",
      "days": "30.0"
      }
     ```

**Sample Request**:  
`POST /api/meal-plan`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```
**Response Time**
   `200ms` 

### **16. Get Recipe by Energy**(Implemented)

- **Endpoint:** `GET api/byenergy/energy`

- **Query Parameters:**
  - **minEnergy** (integer, required): The minimum energy for the recipe.
  - **maxEnergy** (integer, required): The maximum energy for the recipe.
  - **limit** (integer, optional): The limit of number of responses (by default 10).

**Sample Request**:  
`GET api/byenergy/energy?minEnergy=-1&maxEnergy=220&&limit=21`

**Example Response:**
  ```json
 "success": true,
    "message": "Recipes fetched successfully",
    "data": [
        {
            "_id": "6405721fa13d0d2d35890e46",
            "Recipe_id": "2831",
            "Calories": "72.0",
            "cook_time": "105",
            "prep_time": "20",
            "servings": "40",
            "Recipe_title": "Roasted Tikel Gomen",
            "total_time": "125",
            "url": "http://allrecipes.com/recipe/246876/roasted-tikel-gomen/",
            "Region": "Rest Africa",
            "Continent": "African",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/3518516.jpg",
            "Carbohydrate, by difference (g)": "1773.0965",
            "Processes": "preheat||drizzle||combine||sprinkle||mix||bake||stirring||season"
        },
        {
            "_id": "6405721fa13d0d2d35890f4a",
            "Recipe_id": "3091",
            "Calories": "161.0",
            "cook_time": "360",
            "prep_time": "15",
            "servings": "6",
            "Recipe_title": "Peking Pork Chops",
            "total_time": "375",
            "url": "http://allrecipes.com/recipe/22219/peking-pork-chops/",
            "Region": "Chinese and Mongolian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/687851.jpg",
            "Carbohydrate, by difference (g)": "1058.7611",
            "Processes": "place||mix||pour||cover||cook||season"
        },
        {
            "_id": "64057221a13d0d2d35891173",
            "Recipe_id": "3644",
            "Calories": "385.0",
            "cook_time": "15",
            "prep_time": "10",
            "servings": "4",
            "Recipe_title": "Vermicelli Pudding",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/228550/vermicelli-pudding/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1207154.jpg",
            "Carbohydrate, by difference (g)": "1159.3042",
            "Processes": "boil||simmer||stir||simmer||remove||heat||stand||stir"
        },
        {
            "_id": "64057221a13d0d2d35891222",
            "Recipe_id": "3819",
            "Calories": "415.0",
            "cook_time": "25",
            "prep_time": "15",
            "servings": "15",
            "Recipe_title": "Layali Libnan (Lebanese Nights)",
            "total_time": "520",
            "url": "http://allrecipes.com/recipe/34791/layali-libnan-lebanese-nights/",
            "Region": "Middle Eastern",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/33875.jpg",
            "Carbohydrate, by difference (g)": "1091.0842",
            "Processes": "pour||boil||heat||reduce||heat||pour||stream||stirring||stir||cook||remove||stir||cool||cover||refrigerate||heat||heat||stir||cook||remove||stir||stir||add||boil||simmer||remove||heat||cover||chill||serve||spread||cream||sprinkle||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d3589125e",
            "Recipe_id": "3879",
            "Calories": "463.0",
            "cook_time": "45",
            "prep_time": "15",
            "servings": "12",
            "Recipe_title": "Biko",
            "total_time": "660",
            "url": "http://allrecipes.com/recipe/151155/biko/",
            "Region": "Southeast Asian",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1546028.jpg",
            "Carbohydrate, by difference (g)": "1178.71",
            "Processes": "soak||preheat||grease||cook||stirring||pour||stir||boil||bake||cool||cut||serve"
        },
        {
            "_id": "64057221a13d0d2d35891384",
            "Recipe_id": "4173",
            "Calories": "51.0",
            "cook_time": "120",
            "prep_time": "480",
            "servings": "96",
            "Recipe_title": "Spicy Peach Chutney",
            "total_time": "600",
            "url": "http://allrecipes.com/recipe/75320/spicy-peach-chutney/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1039317.jpg",
            "Carbohydrate, by difference (g)": "1210.9855",
            "Processes": "stir||wrap||boil||cook||stir||remove||wipe||seal||process||cover"
        },
        {
            "_id": "64057223a13d0d2d35891575",
            "Recipe_id": "4670",
            "Calories": "75.0",
            "cook_time": "20",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Marian's Pumpkin Soup",
            "total_time": "40",
            "url": "http://allrecipes.com/recipe/143010/marians-pumpkin-soup/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1070713.jpg",
            "Carbohydrate, by difference (g)": "1186.2905",
            "Processes": "melt||heat||add||cook||stir||transfer||stir||cook||remove||heat||stir||transfer||blend||garnish"
        },
        {
            "_id": "64057223a13d0d2d358915b3",
            "Recipe_id": "4732",
            "Calories": "142.0",
            "cook_time": "300",
            "prep_time": "10",
            "servings": "6",
            "Recipe_title": "Korean Slow Cooker Pork Chops",
            "total_time": "310",
            "url": "http://allrecipes.com/recipe/90303/korean-slow-cooker-pork-chops/",
            "Region": "Korean",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1428275.jpg",
            "Carbohydrate, by difference (g)": "1007.3848",
            "Processes": "stir||season||place||cover||cook"
        },
        {
            "_id": "64057223a13d0d2d35891692",
            "Recipe_id": "4955",
            "Calories": "256.0",
            "cook_time": "60",
            "prep_time": "15",
            "servings": "24",
            "Recipe_title": "Butter Mochi",
            "total_time": "195",
            "url": "http://allrecipes.com/recipe/174170/butter-mochi/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/814285.jpg",
            "Carbohydrate, by difference (g)": "1027.6838",
            "Processes": "preheat||grease||whisk||beat||smooth||whisk||stir||scrape||smooth||bake||cool||serve"
        },
        {
            "_id": "64057223a13d0d2d358916fe",
            "Recipe_id": "5063",
            "Calories": "920.0",
            "cook_time": "10",
            "prep_time": "5",
            "servings": "6",
            "Recipe_title": "Tempura Shrimp",
            "total_time": "135",
            "url": "http://allrecipes.com/recipe/12834/tempura-shrimp/",
            "Region": "Japanese",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1071530.jpg",
            "Carbohydrate, by difference (g)": "1955.4975",
            "Processes": "refrigerate||stir||heat||heat||stirring||boil||heat||dip||fry||drain||serve"
        },
        {
            "_id": "64057223a13d0d2d35891751",
            "Recipe_id": "5146",
            "Calories": "394.0",
            "cook_time": "40",
            "prep_time": "10",
            "servings": "16",
            "Recipe_title": "Sweet Rice (Zarda)",
            "total_time": "50",
            "url": "http://allrecipes.com/recipe/22750/sweet-rice-zarda/",
            "Region": "Indian Subcontinent",
            "Continent": "Asian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1662003.jpg",
            "Carbohydrate, by difference (g)": "1400.9035",
            "Processes": "place||cover||boil||stir||heat||cover||simmer||heat||cook||stir||cover||cook||remove||heat||stir||cream||zest||serve"
        },
        {
            "_id": "64057223a13d0d2d358918d2",
            "Recipe_id": "5531",
            "Calories": "116.0",
            "cook_time": "45",
            "prep_time": "30",
            "servings": "64",
            "Recipe_title": "Kumquat Marmalade",
            "total_time": "795",
            "url": "http://allrecipes.com/recipe/46310/kumquat-marmalade/",
            "Region": "Australian",
            "Continent": "Australasian",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/10074.jpg",
            "Carbohydrate, by difference (g)": "1909.4044",
            "Processes": "chop||add||stand||boil||heat||simmer||remove||heat||add||mix||boil||boil||stirring||remove||heat||transfer||process||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891a1f",
            "Recipe_id": "5864",
            "Calories": "626.0",
            "cook_time": "0",
            "prep_time": "0",
            "servings": "4",
            "Recipe_title": "Southwest BBQ Chicken Tacos",
            "total_time": "0",
            "url": "http://allrecipes.com/recipe/255692/southwest-bbq-chicken-tacos/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/4023537.jpg",
            "Carbohydrate, by difference (g)": "1062.8344",
            "Processes": "combine||heat||add||cook||stir||add||cook||heat||top||serve"
        },
        {
            "_id": "64057226a13d0d2d35891a2f",
            "Recipe_id": "5880",
            "Calories": "436.0",
            "cook_time": "285",
            "prep_time": "60",
            "servings": "36",
            "Recipe_title": "Sylvia's Pork Tamales",
            "total_time": "405",
            "url": "http://allrecipes.com/recipe/235668/sylvias-pork-tamales/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1078062.jpg",
            "Carbohydrate, by difference (g)": "1760.7546",
            "Processes": "place||cover||simmer||strain||heat||heat||cook||stir||boil||add||boil||drain||cool||blend||smooth||stir||melt||heat||stir||stir||remove||soak||drain||cover||mix||lard||select||spread||fold||fold||place||boil||add||cook||set"
        },
        {
            "_id": "64057226a13d0d2d35891b07",
            "Recipe_id": "6096",
            "Calories": "557.0",
            "cook_time": "35",
            "prep_time": "30",
            "servings": "16",
            "Recipe_title": "Make Ahead Lunch Wraps",
            "total_time": "65",
            "url": "http://allrecipes.com/recipe/58246/make-ahead-lunch-wraps/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/1053890.jpg",
            "Carbohydrate, by difference (g)": "1021.8721",
            "Processes": "combine||boil||reduce||heat||cover||simmer||remove||heat||cool||place||rinse||add||mix||transfer||mix||divide||wrap||place||reheat"
        },
        {
            "_id": "64057226a13d0d2d35891bc2",
            "Recipe_id": "6283",
            "Calories": "534.0",
            "cook_time": "5",
            "prep_time": "20",
            "servings": "8",
            "Recipe_title": "Refrigerator Lemon Margarita Pie",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/221231/refrigerator-lemon-margarita-pie/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/874792.jpg",
            "Carbohydrate, by difference (g)": "1683.2823",
            "Processes": "mix||press||whisk||stir||boil||heat||stirring||remove||cool||whisk||refrigerate"
        },
        {
            "_id": "64057226a13d0d2d35891cd1",
            "Recipe_id": "6555",
            "Calories": "496.0",
            "cook_time": "35",
            "prep_time": "20",
            "servings": "10",
            "Recipe_title": "Raspados de Tamarindo (Tamarind Ices)",
            "total_time": "55",
            "url": "http://allrecipes.com/recipe/231800/raspados-de-tamarindo-tamarind-ices/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/images/79591.png",
            "Carbohydrate, by difference (g)": "1381.64",
            "Processes": "place||cover||boil||reduce||heat||simmer||strain||add||place||cook||stir||add||divide||pour||serve"
        },
        {
            "_id": "64057229a13d0d2d35891d51",
            "Recipe_id": "6683",
            "Calories": "555.0",
            "cook_time": "20",
            "prep_time": "80",
            "servings": "8",
            "Recipe_title": "Amazing Southwest Cilantro Lime Mango Grilled Chicken Sandwiches",
            "total_time": "100",
            "url": "http://allrecipes.com/recipe/143458/amazing-southwest-cilantro-lime-mango-grilled-chicken-sandwiches/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/2026889.jpg",
            "Carbohydrate, by difference (g)": "1226.1741",
            "Processes": "place||stir||place||pour||seal||coat||refrigerate||combine||cover||refrigerate||prepare||set||whisk||cover||refrigerate||preheat||heat||remove||slice||spread||top"
        },
        {
            "_id": "64057229a13d0d2d35891dde",
            "Recipe_id": "6824",
            "Calories": "617.0",
            "cook_time": "60",
            "prep_time": "25",
            "servings": "10",
            "Recipe_title": "Paella",
            "total_time": "85",
            "url": "http://allrecipes.com/recipe/34413/paella/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/560x315/29333.jpg",
            "Carbohydrate, by difference (g)": "1547.5198",
            "Processes": "heat||heat||fry||remove||fry||remove||stir||cook||stir||mix||add||cover||simmer||add||simmer||stir||cover||cook"
        },
        {
            "_id": "64057229a13d0d2d35891fea",
            "Recipe_id": "7348",
            "Calories": "709.0",
            "cook_time": "20",
            "prep_time": "25",
            "servings": "4",
            "Recipe_title": "Cheese and Beef Enchiladas",
            "total_time": "45",
            "url": "http://allrecipes.com/recipe/213918/cheese-and-beef-enchiladas/",
            "Region": "Mexican",
            "Continent": "Latin American",
            "img_url": "https://images.media-allrecipes.com/userphotos/250x250/990939.jpg",
            "Carbohydrate, by difference (g)": "1050.893",
            "Processes": "heat||heat||add||cook||stirring||drain||add||simmer||stirring||sprinkle||place||cover||uncover||sprinkle||bake||serve"
        }
    ]
  ```

**Error Responses:**
1. **minEnergy > maxEnergy:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified Energy range"
     }
     ```
2. **Database error:**
   - **Status Code:** `500 Bad Request`
   - **Response Body:**
     ```json
     {
         "success": false,
          "message": "No recipes found in the specified carbohydrate range"
     }
     ```

2. **No Recipes Found:**
   - **Status Code:** `200 ok`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found in the specified range."
     }
     ```
**Response Time**
   `200ms` 





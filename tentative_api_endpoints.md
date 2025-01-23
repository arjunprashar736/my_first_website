
## **Recipe API Endpoints**

### **1. Search Recipes by title** - (Implemented)
- **Endpoint:** `GET api/recipe-bytitle/recipeByTitle`
- **Query Parameters:**
  - `title` (string, required): Recipe name or title.
- **Description:** Search for recipes by name/title . The `recipetitle` parameter is used to search for recipes that match the name or contain the specified ingredient.
- **Example Request:**
  ```
  GET /api/recipe-bytitle/recipeByTitle?title=Dukkah)
  ```
- **Example Response:**
  ```json
  {"success":true,"message":"Recipes fetched successfully.","data":[{"_id":"6405721fa13d0d2d35890d6d","Recipe_id":"2614","Calories":"45.0","cook_time":"5","prep_time":"20","servings":"24","Recipe_title":"Dukkah","total_time":"25","Region":"Middle Eastern","Continent":"African"},{"_id":"64057243a13d0d2d35894c9e","Recipe_id":"47216","Calories":"96.9","cook_time":"0","prep_time":"0","servings":"4","Recipe_title":"Dukkah","total_time":"10","Region":"Middle Eastern","Continent":"African"},{"_id":"64057243a13d0d2d35894ca2","Recipe_id":"47220","Calories":"341.6","cook_time":"0","prep_time":"0","servings":"4 eggs","Recipe_title":"Egyptian Eggs With Dukkah","total_time":"15","Region":"Middle Eastern","Continent":"African"},{"_id":"64057243a13d0d2d35894cee","Recipe_id":"47296","Calories":"141.0","cook_time":"0","prep_time":"0","servings":"1 dip","Recipe_title":"Cousin Pete's Yummiest Dukkah (Nut Dip)","total_time":"25","Region":"Middle Eastern","Continent":"African"},{"_id":"64057243a13d0d2d35894cf7","Recipe_id":"47305","Calories":"260.5","cook_time":"0","prep_time":"0","servings":"4","Recipe_title":"Chargrilled Vegetable and Pita Salad With Feta and Dukkah","total_time":"20","Region":"Middle Eastern","Continent":"African"},{"_id":"64057243a13d0d2d35894d2f","Recipe_id":"47361","Calories":"1007.7","cook_time":"0","prep_time":"0","servings":"2 cups","Recipe_title":"Dukkah","total_time":"20","Region":"Middle Eastern","Continent":"African"},{"_id":"64057245a13d0d2d35895308","Recipe_id":"48859","Calories":"188.2","cook_time":"0","prep_time":"0","servings":"16 balls","Recipe_title":"Labna Balls Rolled in Tunisian Dukkah","total_time":"1470","Region":"Rest Africa","Continent":"African"},{"_id":"64057245a13d0d2d358953b2","Recipe_id":"49029","Calories":"790.2","cook_time":"0","prep_time":"0","servings":"3/4 cup","Recipe_title":"Almond Dukkah","total_time":"22","Region":"Rest Africa","Continent":"African"},{"_id":"6405724aa13d0d2d358957b1","Recipe_id":"50053","Calories":"196.1","cook_time":"0","prep_time":"0","servings":"6","Recipe_title":"Brie With Dukkah","total_time":"20","Region":"Northern Africa","Continent":"African"},{"_id":"6405725ea13d0d2d35897f3d","Recipe_id":"60187","Calories":"277.5","cook_time":"0","prep_time":"0","servings":"6","Recipe_title":"Dukkah","total_time":"30","Region":"Middle Eastern","Continent":"Asian"},{"_id":"64057262a13d0d2d3589840c","Recipe_id":"61418","Calories":"103.2","cook_time":"0","prep_time":"0","servings":"4 1/2 pint jars","Recipe_title":"Darcey's Special Dukkah","total_time":"20","Region":"Middle Eastern","Continent":"Asian"},{"_id":"64057262a13d0d2d3589855c","Recipe_id":"61754","Calories":"76.9","cook_time":"0","prep_time":"0","servings":"24 skewers","Recipe_title":"Chicken Skewers With Dukkah Crust and Balsamic Reduction","total_time":"60","Region":"Middle Eastern","Continent":"Asian"},{"_id":"64057277a13d0d2d3589a553","Recipe_id":"69938","Calories":"2866.2","cook_time":"0","prep_time":"0","servings":"1 jar","Recipe_title":"Dukkah","total_time":"60","Region":"Middle Eastern","Continent":"Asian"},{"_id":"6405727da13d0d2d3589ae5c","Recipe_id":"72252","Calories":"218.3","cook_time":"0","prep_time":"0","servings":"3 cups","Recipe_title":"Dukkah (Spicy Nut Mix for Dipping With Flatbread)","total_time":"35","Region":"Indian Subcontinent","Continent":"Asian"},{"_id":"6405727da13d0d2d3589b020","Recipe_id":"72704","Calories":"239.4","cook_time":"0","prep_time":"0","servings":"8","Recipe_title":"Prawns With Chilli Mayo & Pistachio Dukkah","total_time":"20","Region":"Australian","Continent":"Australasian"},{"_id":"6405727fa13d0d2d3589b559","Recipe_id":"74043","Calories":"5545.7","cook_time":"0","prep_time":"0","servings":"1 loaf","Recipe_title":"Garlic  Dukkah  Bread","total_time":"40","Region":"Australian","Continent":"Australasian"},{"_id":"64057286a13d0d2d3589bf35","Recipe_id":"76569","Calories":"346.9","cook_time":"0","prep_time":"0","servings":"6","Recipe_title":"Dukkah Crusted Lamb, Apricot Salsa, Herb Salad With Chermoula D","total_time":"40","Region":"Australian","Continent":"Australasian"},{"_id":"64057288a13d0d2d3589c355","Recipe_id":"77625","Calories":"260.6","cook_time":"0","prep_time":"0","servings":"4","Recipe_title":"Dukkah Spiced Carrot & Feta Salad","total_time":"40","Region":"Australian","Continent":"Australasian"}]}
  ```
- **Error Handling:**
  - If `recipeName` is not provided:
    ```json
    {
      "message": "Recipe name is required"
    }
    ```
  - If `page` or `limit` parameters are invalid:
    ```json
    {
      "message": "Invalid pagination parameters. Page and limit must be positive integers."
    }
    ```
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
---

### 2. Get Recipe Details - (Implemented)

**Endpoint**: `GET /api/recipes/recipe/:id`

**Parameters**:  
- `id` (integer): Recipe ID.

**Description**: Fetch the detailed information for a specific recipe.

**Sample Request**:  
`GET /api/recipes/recipe/2610`

**Example Response**:
```json
{
   "_id": "6775291c2b68f56a4408dd7c",
   "Recipe ID": 2610,
   "ingredient_phrase": "['3 cups water', '1 cup red lentils', '1 roma tomato , quartered', '1 carrot , quartered', '1 small onion , quartered', '4 cloves garlic , quartered', '2 teaspoons ground cumin', '1/2 teaspoon sea salt', '1/2 teaspoon cracked black pepper', '1/4 teaspoon ground coriander']",
   "continent": "African",
   "region": "Middle Eastern",
   "sub_region": "Egyptian",
   "instructions": "['Place 3 cups water, lentils, tomato, carrot, onion, garlic, and chicken bouillon in a stockpot over medium heat.', 'Cook until vegetables and lentils are softened, 20 to 25 minutes. Remove from heat and cool to lukewarm. Blend vegetable and lentil mixture with an immersion blender until smooth. Stir 1 cup water, cumin, sea salt, pepper, and coriander into soup.', 'Heat over medium heat until warmed.']",
   "Recipe Name": "Egyptian Lentil Soup",
   "Recipe Ingredient": "['black pepper', 'cumin', 'garlic', 'sea salt', 'carrot', 'coriander', 'red lentil', 'water', 'onion', 'rom tomato']",
   "Total Ingredient": 10,
   "Available Ingredients": "['cumin', 'garlic', 'carrot', 'coriander', 'red lentil', 'water', 'onion', 'rom tomato']",
   "Available Count": 8,
   "Not Available Ingredients": "['black pepper', 'sea salt']",
   "Not Available Count": 2,
   "Available Percentage": 80,
   "Carbon_footprint_sum": 5.56,
   "Vegetarian_Recipe": 1,
   "Non_Vegetarian_Recipe": 0,
   "Miscellaneous_Recipe": 0
}
```

---

### 3. Get Carbon Footprint by Ingredient - (Implemented)

**Endpoint**: `GET /api/ingredients/:name/carbon-footprint`

**Parameters**:  
- `name` (string): Ingredient name.

**Description**: Fetch the carbon footprint of a specific ingredient.

**Sample Request**:  
`GET /api/ingredients/onion/carbon-footprint`

**Example Response**:
```json
{
   "ingredient": "onion",
   "carbonFootprint": 0.24
}
```
---

### **4. Get Recipe by Ingredient**(Implemented)

- **Endpoint:** `GET /api/recipes/by-ingredient`

- **Query Parameters:**
  - **ingredient** (string, required): Specifies ingredients to include or exclude in the recipes. Use `@` to include, `!` to exclude, and `|` to specify optional ingredients (OR conditions).
  - **page** (integer, optional): Specifies the page number for pagination (default is 1).
  - **limit** (integer, optional): Specifies the number of recipes to return per page (default is 10).

#### **Request Query Format:**
- **@ingredient**: Specifies that the ingredient must be included in the recipe.
- **!ingredient**: Specifies that the ingredient must be excluded from the recipe.
- **|ingredient**: Specifies optional ingredients that can appear in the recipe.

#### **Example Requests:**
1. Search for recipes containing `cumin` but excluding `garlic`:
   ```plaintext
   GET /api/recipes/by-ingredient?ingredient=@cumin !garlic
   ```
2. Search for recipes containing `coriander` but excluding `tomato`, and optionally containing `ginger` or `turmeric`:
   ```plaintext
   GET /api/recipes/by-ingredient?ingredient=@coriander !tomato |ginger |turmeric
   ```
3. Search for recipes containing `salt` or `pepper`:
   ```plaintext
   GET /api/recipes/by-ingredient?ingredient=|salt |pepper
   ```

#### **Response Format:**
- **Status Code:** `200 OK`
- **Response Body:**
  ```json
  {
    "page": 1,
    "limit": 10,
    "totalResults": 25,
    "totalPages": 3,
    "recipes": [
      {
        "_id": "6775291c2b68f56a4408dd80",
        "recipe_id": 2614,
        "recipe_name": "Dukkah",
        "recipe_ingredients": [
          "black pepper", "sea salt", "cumin seed", "coriander seed", "sesame seed", "hazelnut"
        ],
        "total_ingredients": 6,
        "available_ingredients": [
          "coriander seed", "sesame seed", "hazelnut"
        ],
        "available_count": 3,
        "not_available_ingredients": [
          "black pepper", "sea salt", "cumin seed"
        ],
        "not_available_count": 3,
        "available_percentage": 50,
        "continent": "African",
        "region": "Middle Eastern",
        "sub_region": "Egyptian",
        "instructions": [
          "Preheat the oven to 350 degrees F. Place the hazelnuts on a baking sheet, and bake for about 5 minutes...",
          "In a dry skillet over medium heat, toast the sesame seeds until light golden brown...",
          "Process the ingredients and season with salt and pepper, mixing well."
        ],
        "carbon_footprint_sum": 2.27,
        "vegetarian_recipe": true,
        "non_vegetarian_recipe": false,
        "miscellaneous_recipe": false
      }
    ]
  }
  ```

#### **Error Responses:**
1. **Missing Ingredient Parameter:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
       "message": "Ingredient parameter is required."
     }
     ```

2. **Invalid Pagination Parameters:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
       "message": "Page and limit must be positive integers."
     }
     ```

3. **Ingredient Conflict:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
       "message": "Invalid query: Ingredient(s) cannot be in both AND (@), OR (|), and NOT (!) conditions."
     }
     ```
   - **Description:** This error occurs when an ingredient is specified in multiple conditions (`@`, `!`, `|`).

4. **No Recipes Found:**
   - **Status Code:** `200 OK`
   - **Response Body:**
     ```json
     {
       "message": "No recipes found."
     }
     ```

5. **Pagination Out of Range:**
   - **Status Code:** `400 Bad Request`
   - **Response Body:**
     ```json
     {
       "message": "Page number exceeds the total number of pages. Please provide a valid page number."
     }
     ```

6. **Internal Server Error:**
   - **Status Code:** `500 Internal Server Error`
   - **Response Body:**
     ```json
     {
       "message": "Internal Server Error"
     }
     ```

### **Key Points:**
- **Ingredient with `@`**: Specifies that the ingredient must be included in the recipe (logical AND condition).
- **Ingredient with `!`**: Specifies that the ingredient must be excluded from the recipe (logical NOT condition).
- **Ingredient with `|`**: Specifies that the ingredient is optional and can appear in the recipe (logical OR condition).
- **Case Insensitivity**: The search is case-insensitive for all ingredients.
- **Pagination**: Results are returned with pagination details: `totalResults`, `totalPages`, `page`, and `limit`.
- **Conflict**: Conflicts between conditions (`@`, `!`, `|`) will result in an error.
---

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


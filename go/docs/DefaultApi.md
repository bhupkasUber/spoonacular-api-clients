# com.spoonacular.client\DefaultApi

All URIs are relative to *https://api.spoonacular.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AnalyzeARecipeSearchQuery**](DefaultApi.md#AnalyzeARecipeSearchQuery) | **Get** /recipes/queries/analyze | Analyze a Recipe Search Query
[**AnalyzeRecipeInstructions**](DefaultApi.md#AnalyzeRecipeInstructions) | **Post** /recipes/analyzeInstructions | Analyze Recipe Instructions
[**AutocompleteIngredientSearch**](DefaultApi.md#AutocompleteIngredientSearch) | **Get** /food/ingredients/autocomplete | Autocomplete Ingredient Search
[**AutocompleteMenuItemSearch**](DefaultApi.md#AutocompleteMenuItemSearch) | **Get** /food/menuItems/suggest | Autocomplete Menu Item Search
[**AutocompleteProductSearch**](DefaultApi.md#AutocompleteProductSearch) | **Get** /food/products/suggest | Autocomplete Product Search
[**AutocompleteRecipeSearch**](DefaultApi.md#AutocompleteRecipeSearch) | **Get** /recipes/autocomplete | Autocomplete Recipe Search
[**ClassifyCuisine**](DefaultApi.md#ClassifyCuisine) | **Post** /recipes/cuisine | Classify Cuisine
[**ClassifyGroceryProduct**](DefaultApi.md#ClassifyGroceryProduct) | **Post** /food/products/classify | Classify Grocery Product
[**ClassifyGroceryProductBulk**](DefaultApi.md#ClassifyGroceryProductBulk) | **Post** /food/products/classifyBatch | Classify Grocery Product Bulk
[**ConvertAmounts**](DefaultApi.md#ConvertAmounts) | **Get** /recipes/convert | Convert Amounts
[**CreateRecipeCard**](DefaultApi.md#CreateRecipeCard) | **Post** /recipes/visualizeRecipe | Create Recipe Card
[**DetectFoodInText**](DefaultApi.md#DetectFoodInText) | **Post** /food/detect | Detect Food in Text
[**ExtractRecipeFromWebsite**](DefaultApi.md#ExtractRecipeFromWebsite) | **Get** /recipes/extract | Extract Recipe from Website
[**GenerateMealPlan**](DefaultApi.md#GenerateMealPlan) | **Get** /mealplanner/generate | Generate Meal Plan
[**GetARandomFoodJoke**](DefaultApi.md#GetARandomFoodJoke) | **Get** /food/jokes/random | Get a Random Food Joke
[**GetAnalyzedRecipeInstructions**](DefaultApi.md#GetAnalyzedRecipeInstructions) | **Get** /recipes/{id}/analyzedInstructions | Get Analyzed Recipe Instructions
[**GetComparableProducts**](DefaultApi.md#GetComparableProducts) | **Get** /food/products/upc/{upc}/comparable | Get Comparable Products
[**GetConversationSuggests**](DefaultApi.md#GetConversationSuggests) | **Get** /food/converse/suggest | Get Conversation Suggests
[**GetDishPairingForWine**](DefaultApi.md#GetDishPairingForWine) | **Get** /food/wine/dishes | Get Dish Pairing for Wine
[**GetIngredientInformation**](DefaultApi.md#GetIngredientInformation) | **Get** /food/ingredients/{id}/information | Get Ingredient Information
[**GetIngredientSubstitutes**](DefaultApi.md#GetIngredientSubstitutes) | **Get** /food/ingredients/substitutes | Get Ingredient Substitutes
[**GetIngredientSubstitutesByID**](DefaultApi.md#GetIngredientSubstitutesByID) | **Get** /food/ingredients/{id}/substitutes | Get Ingredient Substitutes by ID
[**GetMenuItemInformation**](DefaultApi.md#GetMenuItemInformation) | **Get** /food/menuItems/{id} | Get Menu Item Information
[**GetProductInformation**](DefaultApi.md#GetProductInformation) | **Get** /food/products/{id} | Get Product Information
[**GetRandomFoodTrivia**](DefaultApi.md#GetRandomFoodTrivia) | **Get** /food/trivia/random | Get Random Food Trivia
[**GetRandomRecipes**](DefaultApi.md#GetRandomRecipes) | **Get** /recipes/random | Get Random Recipes
[**GetRecipeEquipmentByID**](DefaultApi.md#GetRecipeEquipmentByID) | **Get** /recipes/{id}/equipmentWidget.json | Get Recipe Equipment by ID
[**GetRecipeInformation**](DefaultApi.md#GetRecipeInformation) | **Get** /recipes/{id}/information | Get Recipe Information
[**GetRecipeInformationBulk**](DefaultApi.md#GetRecipeInformationBulk) | **Get** /recipes/informationBulk | Get Recipe Information Bulk
[**GetRecipeIngredientsByID**](DefaultApi.md#GetRecipeIngredientsByID) | **Get** /recipes/{id}/ingredientWidget.json | Get Recipe Ingredients by ID
[**GetRecipeNutritionWidgetByID**](DefaultApi.md#GetRecipeNutritionWidgetByID) | **Get** /recipes/{id}/nutritionWidget.json | Get Recipe Nutrition Widget by ID
[**GetRecipePriceBreakdownByID**](DefaultApi.md#GetRecipePriceBreakdownByID) | **Get** /recipes/{id}/priceBreakdownWidget.json | Get Recipe Price Breakdown by ID
[**GetSimilarRecipes**](DefaultApi.md#GetSimilarRecipes) | **Get** /recipes/{id}/similar | Get Similar Recipes
[**GetWineDescription**](DefaultApi.md#GetWineDescription) | **Get** /food/wine/description | Get Wine Description
[**GetWinePairing**](DefaultApi.md#GetWinePairing) | **Get** /food/wine/pairing | Get Wine Pairing
[**GetWineRecommendation**](DefaultApi.md#GetWineRecommendation) | **Get** /food/wine/recommendation | Get Wine Recommendation
[**GuessNutritionByDishName**](DefaultApi.md#GuessNutritionByDishName) | **Get** /recipes/guessNutrition | Guess Nutrition by Dish Name
[**MapIngredientsToGroceryProducts**](DefaultApi.md#MapIngredientsToGroceryProducts) | **Post** /food/ingredients/map | Map Ingredients to Grocery Products
[**ParseIngredients**](DefaultApi.md#ParseIngredients) | **Post** /recipes/parseIngredients | Parse Ingredients
[**QuickAnswer**](DefaultApi.md#QuickAnswer) | **Get** /recipes/quickAnswer | Quick Answer
[**SearchFoodVideos**](DefaultApi.md#SearchFoodVideos) | **Get** /food/videos/search | Search Food Videos
[**SearchGroceryProducts**](DefaultApi.md#SearchGroceryProducts) | **Get** /food/products/search | Search Grocery Products
[**SearchGroceryProductsByUPC**](DefaultApi.md#SearchGroceryProductsByUPC) | **Get** /food/products/upc/{upc} | Search Grocery Products by UPC
[**SearchMenuItems**](DefaultApi.md#SearchMenuItems) | **Get** /food/menuItems/search | Search Menu Items
[**SearchRecipes**](DefaultApi.md#SearchRecipes) | **Get** /recipes/search | Search Recipes
[**SearchRecipesByIngredients**](DefaultApi.md#SearchRecipesByIngredients) | **Get** /recipes/findByIngredients | Search Recipes by Ingredients
[**SearchRecipesByNutrients**](DefaultApi.md#SearchRecipesByNutrients) | **Get** /recipes/findByNutrients | Search Recipes by Nutrients
[**SearchRecipesComplex**](DefaultApi.md#SearchRecipesComplex) | **Get** /recipes/complexSearch | Search Recipes Complex
[**SearchSiteContent**](DefaultApi.md#SearchSiteContent) | **Get** /food/site/search | Search Site Content
[**SummarizeRecipe**](DefaultApi.md#SummarizeRecipe) | **Get** /recipes/{id}/summary | Summarize Recipe
[**TalkToChatbot**](DefaultApi.md#TalkToChatbot) | **Get** /food/converse | Talk to Chatbot
[**VisualizeEquipment**](DefaultApi.md#VisualizeEquipment) | **Post** /recipes/visualizeEquipment | Visualize Equipment
[**VisualizeIngredients**](DefaultApi.md#VisualizeIngredients) | **Post** /recipes/visualizeIngredients | Visualize Ingredients
[**VisualizeMenuItemNutritionByID**](DefaultApi.md#VisualizeMenuItemNutritionByID) | **Get** /food/menuItems/{id}/nutritionWidget | Visualize Menu Item Nutrition by ID
[**VisualizePriceBreakdown**](DefaultApi.md#VisualizePriceBreakdown) | **Post** /recipes/visualizePriceEstimator | Visualize Price Breakdown
[**VisualizeProductNutritionByID**](DefaultApi.md#VisualizeProductNutritionByID) | **Get** /food/products/{id}/nutritionWidget | Visualize Product Nutrition by ID
[**VisualizeRecipeEquipmentByID**](DefaultApi.md#VisualizeRecipeEquipmentByID) | **Get** /recipes/{id}/equipmentWidget | Visualize Recipe Equipment by ID
[**VisualizeRecipeIngredientsByID**](DefaultApi.md#VisualizeRecipeIngredientsByID) | **Get** /recipes/{id}/ingredientWidget | Visualize Recipe Ingredients by ID
[**VisualizeRecipeNutrition**](DefaultApi.md#VisualizeRecipeNutrition) | **Post** /recipes/visualizeNutrition | Visualize Recipe Nutrition
[**VisualizeRecipeNutritionByID**](DefaultApi.md#VisualizeRecipeNutritionByID) | **Get** /recipes/{id}/nutritionWidget | Visualize Recipe Nutrition by ID
[**VisualizeRecipePriceBreakdownByID**](DefaultApi.md#VisualizeRecipePriceBreakdownByID) | **Get** /recipes/{id}/priceBreakdownWidget | Visualize Recipe Price Breakdown by ID



## AnalyzeARecipeSearchQuery

> map[string]interface{} AnalyzeARecipeSearchQuery(ctx, q)
Analyze a Recipe Search Query

Parse a recipe search query to find out its intention.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**q** | **string**| The recipe search query. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AnalyzeRecipeInstructions

> map[string]interface{} AnalyzeRecipeInstructions(ctx, instructions)
Analyze Recipe Instructions

Extract ingredients and equipment from the recipe's instructions.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instructions** | **string**| The instructions to be analyzed. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AutocompleteIngredientSearch

> map[string]interface{} AutocompleteIngredientSearch(ctx, query, optional)
Autocomplete Ingredient Search

Autocomplete the entry of an ingredient.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The partial or full ingredient name. | 
 **optional** | ***AutocompleteIngredientSearchOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a AutocompleteIngredientSearchOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The number of results to return (between 1 and 100). | 
 **metaInformation** | **optional.Bool**| Whether to return more meta information about the ingredients. | 
 **intolerances** | **optional.Bool**| A comma-separated list of intolerances. All recipes returned must not contain ingredients that are not suitable for people with the intolerances entered. See a full list of supported intolerances. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AutocompleteMenuItemSearch

> map[string]interface{} AutocompleteMenuItemSearch(ctx, query, optional)
Autocomplete Menu Item Search

Generate suggestions for menu items based on a (partial) query. The matches will be found by looking in the title only.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The (partial) search query. | 
 **optional** | ***AutocompleteMenuItemSearchOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a AutocompleteMenuItemSearchOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The number of results to return (between 1 and 25). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AutocompleteProductSearch

> map[string]interface{} AutocompleteProductSearch(ctx, query, optional)
Autocomplete Product Search

Generate suggestions for grocery products based on a (partial) query. The matches will be found by looking in the title only.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The (partial) search query. | 
 **optional** | ***AutocompleteProductSearchOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a AutocompleteProductSearchOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The number of results to return (between 1 and 25). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AutocompleteRecipeSearch

> map[string]interface{} AutocompleteRecipeSearch(ctx, query, optional)
Autocomplete Recipe Search

Autocomplete a partial input to suggest possible recipe names.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The query to be autocompleted. | 
 **optional** | ***AutocompleteRecipeSearchOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a AutocompleteRecipeSearchOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The number of results to return (between 1 and 25). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClassifyCuisine

> map[string]interface{} ClassifyCuisine(ctx, title, ingredientList)
Classify Cuisine

Classify the recipe's cuisine.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**title** | **string**| The title of the recipe. | 
**ingredientList** | **string**| The ingredient list of the recipe, one ingredient per line (separate lines with \\\\n). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClassifyGroceryProduct

> map[string]interface{} ClassifyGroceryProduct(ctx, inlineObject8, optional)
Classify Grocery Product

This endpoint allows you to match a packaged food to a basic category, e.g. a specific brand of milk to the category milk.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**inlineObject8** | [**InlineObject8**](InlineObject8.md)|  | 
 **optional** | ***ClassifyGroceryProductOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a ClassifyGroceryProductOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **locale** | **optional.String**| The display name of the returned category, supported is en_US (for American English) and en_GB (for British English). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClassifyGroceryProductBulk

> map[string]interface{} ClassifyGroceryProductBulk(ctx, body, optional)
Classify Grocery Product Bulk

Provide a set of product jsons, get back classified products.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**body** | **map[string]interface{}**|  | 
 **optional** | ***ClassifyGroceryProductBulkOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a ClassifyGroceryProductBulkOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **locale** | **optional.String**| The display name of the returned category, supported is en_US (for American English) and en_GB (for British English). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConvertAmounts

> map[string]interface{} ConvertAmounts(ctx, ingredientName, sourceAmount, sourceUnit, targetUnit)
Convert Amounts

Convert amounts like \"2 cups of flour to grams\".

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientName** | **string**| The ingredient which you want to convert. | 
**sourceAmount** | **float32**| The amount from which you want to convert, e.g. the 2.5 in \&quot;2.5 cups of flour to grams\&quot;. | 
**sourceUnit** | **string**| The unit from which you want to convert, e.g. the grams in \&quot;2.5 cups of flour to grams\&quot;. You can also use \&quot;piece\&quot;, e.g. \&quot;3.4 oz tomatoes to piece\&quot; | 
**targetUnit** | **string**| The unit to which you want to convert, e.g. the grams in \&quot;2.5 cups of flour to grams\&quot;. You can also use \&quot;piece\&quot;, e.g. \&quot;3.4 oz tomatoes to piece\&quot; | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateRecipeCard

> map[string]interface{} CreateRecipeCard(ctx, title, image, ingredients, instructions, readyInMinutes, servings, mask, backgroundImage, optional)
Create Recipe Card

Generate a recipe card for a recipe.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**title** | **string**| The title of the recipe. | 
**image** | ***os.File*****os.File**| The binary image of the recipe as jpg. | 
**ingredients** | **string**| The ingredient list of the recipe, one ingredient per line (separate lines with \\\\n). | 
**instructions** | **string**| The instructions to make the recipe. One step per line (separate lines with \\\\n). | 
**readyInMinutes** | **float32**| The number of minutes it takes to get the recipe on the table. | 
**servings** | **float32**| The number of servings the recipe makes. | 
**mask** | **string**| The mask to put over the recipe image (\\\&quot;ellipseMask\\\&quot;, \\\&quot;diamondMask\\\&quot;, \\\&quot;starMask\\\&quot;, \\\&quot;heartMask\\\&quot;, \\\&quot;potMask\\\&quot;, \\\&quot;fishMask\\\&quot;). | 
**backgroundImage** | **string**| The background image (\\\&quot;none\\\&quot;,\\\&quot;background1\\\&quot;, or \\\&quot;background2\\\&quot;). | 
 **optional** | ***CreateRecipeCardOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a CreateRecipeCardOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------








 **author** | **optional.String**| The author of the recipe. | 
 **backgroundColor** | **optional.String**| The background color for the recipe card as a hex-string. | 
 **fontColor** | **optional.String**| The font color for the recipe card as a hex-string. | 
 **source** | **optional.String**| The source of the recipe. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DetectFoodInText

> map[string]interface{} DetectFoodInText(ctx, text)
Detect Food in Text

Take any text and find all mentions of food contained within it. This task is also called Named Entity Recognition (NER). In this case, the entities are foods. Either dishes, such as pizza or cheeseburger, or ingredients, such as cucumber or almonds.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**text** | **string**| The text in which food items, such as dish names and ingredients, should be detected in. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExtractRecipeFromWebsite

> map[string]interface{} ExtractRecipeFromWebsite(ctx, url, optional)
Extract Recipe from Website

This endpoint lets you extract recipe data such as title, ingredients, and instructions from any properly formatted Website.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**url** | **string**| The URL of the recipe page. | 
 **optional** | ***ExtractRecipeFromWebsiteOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a ExtractRecipeFromWebsiteOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **forceExtraction** | **optional.Bool**| If true, the extraction will be triggered whether we already know the recipe or not. Use this only if information is missing as this operation is slower. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateMealPlan

> map[string]interface{} GenerateMealPlan(ctx, optional)
Generate Meal Plan

Generate a meal plan with three meals per day (breakfast, lunch, and dinner).

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***GenerateMealPlanOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GenerateMealPlanOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **timeFrame** | **optional.String**| Either for one \&quot;day\&quot; or an entire \&quot;week\&quot;. | 
 **targetCalories** | **optional.Float32**| What is the caloric target for one day? The meal plan generator will try to get as close as possible to that goal. | 
 **diet** | **optional.String**| Enter a diet that the meal plan has to adhere to. See a full list of supported diets. | 
 **exclude** | **optional.String**| A comma-separated list of allergens or ingredients that must be excluded. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetARandomFoodJoke

> map[string]interface{} GetARandomFoodJoke(ctx, )
Get a Random Food Joke

Get a random joke that is related to food. Caution: this is an endpoint for adults!

### Required Parameters

This endpoint does not need any parameter.

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAnalyzedRecipeInstructions

> map[string]interface{} GetAnalyzedRecipeInstructions(ctx, id, optional)
Get Analyzed Recipe Instructions

Get an analyzed breakdown of a recipe's instructions. Each step is enriched with the ingredients and equipment required.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 
 **optional** | ***GetAnalyzedRecipeInstructionsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetAnalyzedRecipeInstructionsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **stepBreakdown** | **optional.Bool**| Whether to break down the recipe steps even more. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComparableProducts

> map[string]interface{} GetComparableProducts(ctx, upc)
Get Comparable Products

Find comparable products to the given one.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**upc** | **float32**| The UPC of the product for which you want to find comparable products. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConversationSuggests

> map[string]interface{} GetConversationSuggests(ctx, query, optional)
Get Conversation Suggests

This endpoint returns suggestions for things the user can say or ask the chatbot.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| A (partial) query from the user. The endpoint will return if it matches topics it can talk about. | 
 **optional** | ***GetConversationSuggestsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetConversationSuggestsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The number of suggestions to return (between 1 and 25). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDishPairingForWine

> map[string]interface{} GetDishPairingForWine(ctx, wine)
Get Dish Pairing for Wine

Find a dish that goes well with a given wine.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**wine** | **string**| The type of wine that should be paired, e.g. \&quot;merlot\&quot;, \&quot;riesling\&quot;, or \&quot;malbec\&quot;. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIngredientInformation

> map[string]interface{} GetIngredientInformation(ctx, id, optional)
Get Ingredient Information

Use an ingredient id to get all available information about an ingredient, such as its image and supermarket aisle.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The ingredient id. | 
 **optional** | ***GetIngredientInformationOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetIngredientInformationOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **amount** | **optional.Float32**| The amount of this ingredient. | 
 **unit** | **optional.String**| The unit for the given amount. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIngredientSubstitutes

> map[string]interface{} GetIngredientSubstitutes(ctx, ingredientName)
Get Ingredient Substitutes

Search for substitutes for a given ingredient.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientName** | **string**| The name of the ingredient you want to replace. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIngredientSubstitutesByID

> map[string]interface{} GetIngredientSubstitutesByID(ctx, id)
Get Ingredient Substitutes by ID

Search for substitutes for a given ingredient.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The id of the ingredient you want substitutes for. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMenuItemInformation

> map[string]interface{} GetMenuItemInformation(ctx, id)
Get Menu Item Information

Use a menu item id to get all available information about a menu item, such as nutrition.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The menu item id. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProductInformation

> map[string]interface{} GetProductInformation(ctx, id)
Get Product Information

Use a product id to get full information about a product, such as ingredients, nutrition, etc.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The id of the packaged food. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRandomFoodTrivia

> map[string]interface{} GetRandomFoodTrivia(ctx, )
Get Random Food Trivia

Returns random food trivia.

### Required Parameters

This endpoint does not need any parameter.

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRandomRecipes

> map[string]interface{} GetRandomRecipes(ctx, optional)
Get Random Recipes

Find random (popular) recipes. If you need to filter recipes by diet, nutrition etc. you might want to consider using the complex recipe search endpoint and set the sort request parameter to random.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***GetRandomRecipesOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetRandomRecipesOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limitLicense** | **optional.Bool**| Whether the recipes should have an open license that allows display with proper attribution. | 
 **tags** | **optional.String**| The tags (can be diets, meal types, cuisines, or intolerances) that the recipe must have. | 
 **number** | **optional.Float32**| The number of random recipes to be returned (between 1 and 100). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipeEquipmentByID

> map[string]interface{} GetRecipeEquipmentByID(ctx, id)
Get Recipe Equipment by ID

Get a recipe's equipment list.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipeInformation

> map[string]interface{} GetRecipeInformation(ctx, id, optional)
Get Recipe Information

Use a recipe id to get full information about a recipe, such as ingredients, nutrition, diet and allergen information, etc.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The id of the recipe. | 
 **optional** | ***GetRecipeInformationOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetRecipeInformationOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **includeNutrition** | **optional.Bool**| Include nutrition data in the recipe information. Nutrition data is per serving. If you want the nutrition data for the entire recipe, just multiply by the number of servings. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipeInformationBulk

> map[string]interface{} GetRecipeInformationBulk(ctx, ids, optional)
Get Recipe Information Bulk

Get information about multiple recipes at once. This is equivalent to calling the Get Recipe Information endpoint multiple times, but faster.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ids** | **string**| A comma-separated list of recipe ids. | 
 **optional** | ***GetRecipeInformationBulkOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetRecipeInformationBulkOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **includeNutrition** | **optional.Bool**| Include nutrition data to the recipe information. Nutrition data is per serving. If you want the nutrition data for the entire recipe, just multiply by the number of servings. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipeIngredientsByID

> map[string]interface{} GetRecipeIngredientsByID(ctx, id)
Get Recipe Ingredients by ID

Get a recipe's ingredient list.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipeNutritionWidgetByID

> map[string]interface{} GetRecipeNutritionWidgetByID(ctx, id)
Get Recipe Nutrition Widget by ID

Get a recipe's nutrition widget data.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipePriceBreakdownByID

> map[string]interface{} GetRecipePriceBreakdownByID(ctx, id)
Get Recipe Price Breakdown by ID

Get a recipe's price breakdown data.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSimilarRecipes

> map[string]interface{} GetSimilarRecipes(ctx, id, optional)
Get Similar Recipes

Find recipes which are similar to the given one.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The id of the source recipe for which similar recipes should be found. | 
 **optional** | ***GetSimilarRecipesOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetSimilarRecipesOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The number of random recipes to be returned (between 1 and 100). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWineDescription

> map[string]interface{} GetWineDescription(ctx, wine)
Get Wine Description

Get a simple description of a certain wine, e.g. \"malbec\", \"riesling\", or \"merlot\".

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**wine** | **string**| The name of the wine that should be paired, e.g. \&quot;merlot\&quot;, \&quot;riesling\&quot;, or \&quot;malbec\&quot;. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWinePairing

> map[string]interface{} GetWinePairing(ctx, food, optional)
Get Wine Pairing

Find a wine that goes well with a food. Food can be a dish name (\"steak\"), an ingredient name (\"salmon\"), or a cuisine (\"italian\").

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**food** | **string**| The food to get a pairing for. This can be a dish (\&quot;steak\&quot;), an ingredient (\&quot;salmon\&quot;), or a cuisine (\&quot;italian\&quot;). | 
 **optional** | ***GetWinePairingOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetWinePairingOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **maxPrice** | **optional.Float32**| The maximum price for the specific wine recommendation in USD. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWineRecommendation

> map[string]interface{} GetWineRecommendation(ctx, wine, optional)
Get Wine Recommendation

Get a specific wine recommendation (concrete product) for a given wine type, e.g. \"merlot\".

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**wine** | **string**| The type of wine to get a specific product recommendation for. | 
 **optional** | ***GetWineRecommendationOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a GetWineRecommendationOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **maxPrice** | **optional.Float32**| The maximum price for the specific wine recommendation in USD. | 
 **minRating** | **optional.Float32**| The minimum rating of the recommended wine between 0 and 1. For example, 0.8 equals 4 out of 5 stars. | 
 **number** | **optional.Float32**| The number of wine recommendations expected (between 1 and 100). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GuessNutritionByDishName

> map[string]interface{} GuessNutritionByDishName(ctx, title)
Guess Nutrition by Dish Name

Estimate the macronutrients of a dish based on its title.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**title** | **string**| The title of the dish. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MapIngredientsToGroceryProducts

> map[string]interface{} MapIngredientsToGroceryProducts(ctx, body)
Map Ingredients to Grocery Products

Map a set of ingredients to products you can buy in the grocery store.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**body** | **map[string]interface{}**|  | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ParseIngredients

> map[string]interface{} ParseIngredients(ctx, ingredientList, servings, optional)
Parse Ingredients

Extract an ingredient from plain text.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientList** | **string**| The ingredient list of the recipe, one ingredient per line. | 
**servings** | **float32**| The number of servings that you can make from the ingredients. | 
 **optional** | ***ParseIngredientsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a ParseIngredientsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **includeNutrition** | **optional.Bool**| Whether nutrition data should be added to correctly parsed ingredients. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## QuickAnswer

> map[string]interface{} QuickAnswer(ctx, q)
Quick Answer

Answer a nutrition related natural language question.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**q** | **string**| The nutrition related question. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchFoodVideos

> map[string]interface{} SearchFoodVideos(ctx, query, optional)
Search Food Videos

Find recipe and other food related videos.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The search query. | 
 **optional** | ***SearchFoodVideosOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchFoodVideosOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **optional.String**| The type of the recipes. See a full list of supported meal types. | 
 **cuisine** | **optional.String**| The cuisine(s) of the recipes. One or more, comma separated. See a full list of supported cuisines. | 
 **diet** | **optional.String**| The diet for which the recipes must be suitable. See a full list of supported diets. | 
 **includeIngredients** | **optional.String**| A comma-separated list of ingredients that the recipes should contain. | 
 **excludeIngredients** | **optional.String**| A comma-separated list of ingredients or ingredient types that the recipes must not contain. | 
 **minLength** | **optional.Float32**| Minimum video length in seconds. | 
 **maxLength** | **optional.Float32**| Maximum video length in seconds. | 
 **offset** | **optional.Float32**| The number of results to skip (between 0 and 900). | 
 **number** | **optional.Float32**| The number of results to return (between 1 and 100). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchGroceryProducts

> map[string]interface{} SearchGroceryProducts(ctx, query, optional)
Search Grocery Products

Search packaged food products, such as frozen pizza or Greek yogurt.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The search query. | 
 **optional** | ***SearchGroceryProductsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchGroceryProductsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **minCalories** | **optional.Float32**| The minimum amount of calories the product must have. | 
 **maxCalories** | **optional.Float32**| The maximum amount of calories the product can have. | 
 **minCarbs** | **optional.Float32**| The minimum amount of carbohydrates in grams the product must have. | 
 **maxCarbs** | **optional.Float32**| The maximum amount of carbohydrates in grams the product can have. | 
 **minProtein** | **optional.Float32**| The minimum amount of protein in grams the product must have. | 
 **maxProtein** | **optional.Float32**| The maximum amount of protein in grams the product can have. | 
 **minFat** | **optional.Float32**| The minimum amount of fat in grams the product must have. | 
 **maxFat** | **optional.Float32**| The maximum amount of fat in grams the product can have. | 
 **offset** | **optional.Float32**| The offset number for paging (between 0 and 990). | 
 **number** | **optional.Float32**| The number of expected results (between 1 and 100). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchGroceryProductsByUPC

> map[string]interface{} SearchGroceryProductsByUPC(ctx, upc)
Search Grocery Products by UPC

Get information about a packaged food using its UPC.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**upc** | **float32**| The product&#39;s UPC. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchMenuItems

> map[string]interface{} SearchMenuItems(ctx, query, optional)
Search Menu Items

Search over 115,000 menu items from over 800 fast food and chain restaurants. For example, McDonald's Big Mac or Starbucks Mocha.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The search query. | 
 **optional** | ***SearchMenuItemsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchMenuItemsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **minCalories** | **optional.Float32**| The minimum amount of calories the menu item must have. | 
 **maxCalories** | **optional.Float32**| The maximum amount of calories the menu item can have. | 
 **minCarbs** | **optional.Float32**| The minimum amount of carbohydrates in grams the menu item must have. | 
 **maxCarbs** | **optional.Float32**| The maximum amount of carbohydrates in grams the menu item can have. | 
 **minProtein** | **optional.Float32**| The minimum amount of protein in grams the menu item must have. | 
 **maxProtein** | **optional.Float32**| The maximum amount of protein in grams the menu item can have. | 
 **minFat** | **optional.Float32**| The minimum amount of fat in grams the menu item must have. | 
 **maxFat** | **optional.Float32**| The maximum amount of fat in grams the menu item can have. | 
 **offset** | **optional.Float32**| The offset number for paging (between 0 and 990). | 
 **number** | **optional.Float32**| The number of expected results (between 1 and 10). | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchRecipes

> map[string]interface{} SearchRecipes(ctx, query, optional)
Search Recipes

Our recipe API includes over 360,000 recipes as well as an open source recipe database. Consider using the \"Search Recipes Complex\" endpoint for much more flexibility.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The (natural language) recipe search query. | 
 **optional** | ***SearchRecipesOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchRecipesOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cuisine** | **optional.String**| The cuisine(s) of the recipes. One or more comma separated. See a full list of supported cuisines. | 
 **diet** | **optional.String**| The diet for which the recipes must be suitable. See a full list of supported diets. | 
 **excludeIngredients** | **optional.String**| A comma-separated list of ingredients or ingredient types that the recipes must not contain. | 
 **intolerances** | **optional.String**| A comma-separated list of intolerances. All recipes returned must not contain ingredients that are not suitable for people with the intolerances entered. See a full list of supported intolerances. Please note: due to the automatic nature of the recipe analysis, the API cannot be 100% accurate in all cases. Please advise your users to seek professional help with medical issues. | 
 **offset** | **optional.Float32**| The number of results to skip (between 0 and 900). | 
 **number** | **optional.Float32**| The number of results to return (between 1 and 100). | 
 **limitLicense** | **optional.Bool**| Whether the recipes should have an open license that allows display with proper attribution. | 
 **instructionsRequired** | **optional.Bool**| Whether the recipes must have instructions. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchRecipesByIngredients

> map[string]interface{} SearchRecipesByIngredients(ctx, ingredients, optional)
Search Recipes by Ingredients

Ever wondered what recipes you can cook with the ingredients you have in your fridge or pantry? This endpoint lets you find recipes that either maximize the usage of ingredients you have at hand (pre shopping) or minimize the ingredients that you don't currently have (post shopping).

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredients** | **string**| A comma-separated list of ingredients that the recipes should contain. | 
 **optional** | ***SearchRecipesByIngredientsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchRecipesByIngredientsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **number** | **optional.Float32**| The maximum number of recipes to return (between 1 and 100). Defaults to 10. | 
 **limitLicense** | **optional.Bool**| Whether the recipes should have an open license that allows display with proper attribution. | 
 **ranking** | **optional.Float32**| Whether to maximize used ingredients (1) or minimize missing ingredients (2) first. | 
 **ignorePantry** | **optional.Bool**| Whether to ignore typical pantry items, such as water, salt, flour, etc. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchRecipesByNutrients

> map[string]interface{} SearchRecipesByNutrients(ctx, optional)
Search Recipes by Nutrients

Find a set of recipes that adhere to the given nutritional limits. You may set limits for macronutrients (calories, protein, fat, and carbohydrate) and/or many micronutrients.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***SearchRecipesByNutrientsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchRecipesByNutrientsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **minCarbs** | **optional.Float32**| The minimum amount of carbohydrates in grams the recipe must have. | 
 **maxCarbs** | **optional.Float32**| The maximum amount of carbohydrates in grams the recipe can have. | 
 **minProtein** | **optional.Float32**| The minimum amount of protein in grams the recipe must have. | 
 **maxProtein** | **optional.Float32**| The maximum amount of protein in grams the recipe can have. | 
 **minCalories** | **optional.Float32**| The minimum amount of calories the recipe must have. | 
 **maxCalories** | **optional.Float32**| The maximum amount of calories the recipe can have. | 
 **minFat** | **optional.Float32**| The minimum amount of fat in grams the recipe must have. | 
 **maxFat** | **optional.Float32**| The maximum amount of fat in grams the recipe can have. | 
 **minAlcohol** | **optional.Float32**| The minimum amount of alcohol in grams the recipe must have. | 
 **maxAlcohol** | **optional.Float32**| The maximum amount of alcohol in grams the recipe can have. | 
 **minCaffeine** | **optional.Float32**| The minimum amount of caffeine in milligrams the recipe must have. | 
 **maxCaffeine** | **optional.Float32**| The maximum amount of caffeine in milligrams the recipe can have. | 
 **minCopper** | **optional.Float32**| The minimum amount of copper in milligrams the recipe must have. | 
 **maxCopper** | **optional.Float32**| The maximum amount of copper in milligrams the recipe can have. | 
 **minCalcium** | **optional.Float32**| The minimum amount of calcium in milligrams the recipe must have. | 
 **maxCalcium** | **optional.Float32**| The maximum amount of calcium in milligrams the recipe can have. | 
 **minCholine** | **optional.Float32**| The minimum amount of choline in milligrams the recipe must have. | 
 **maxCholine** | **optional.Float32**| The maximum amount of choline in milligrams the recipe can have. | 
 **minCholesterol** | **optional.Float32**| The minimum amount of cholesterol in milligrams the recipe must have. | 
 **maxCholesterol** | **optional.Float32**| The maximum amount of cholesterol in milligrams the recipe can have. | 
 **minFluoride** | **optional.Float32**| The minimum amount of fluoride in milligrams the recipe must have. | 
 **maxFluoride** | **optional.Float32**| The maximum amount of fluoride in milligrams the recipe can have. | 
 **minSaturatedFat** | **optional.Float32**| The minimum amount of saturated fat in grams the recipe must have. | 
 **maxSaturatedFat** | **optional.Float32**| The maximum amount of saturated fat in grams the recipe can have. | 
 **minVitaminA** | **optional.Float32**| The minimum amount of Vitamin A in IU the recipe must have. | 
 **maxVitaminA** | **optional.Float32**| The maximum amount of Vitamin A in IU the recipe can have. | 
 **minVitaminC** | **optional.Float32**| The minimum amount of Vitamin C in milligrams the recipe must have. | 
 **maxVitaminC** | **optional.Float32**| The maximum amount of Vitamin C in milligrams the recipe can have. | 
 **minVitaminD** | **optional.Float32**| The minimum amount of Vitamin D in micrograms the recipe must have. | 
 **maxVitaminD** | **optional.Float32**| The maximum amount of Vitamin D in micrograms the recipe can have. | 
 **minVitaminE** | **optional.Float32**| The minimum amount of Vitamin E in milligrams the recipe must have. | 
 **maxVitaminE** | **optional.Float32**| The maximum amount of Vitamin E in milligrams the recipe can have. | 
 **minVitaminK** | **optional.Float32**| The minimum amount of Vitamin K in micrograms the recipe must have. | 
 **maxVitaminK** | **optional.Float32**| The maximum amount of Vitamin K in micrograms the recipe can have. | 
 **minVitaminB1** | **optional.Float32**| The minimum amount of Vitamin B1 in milligrams the recipe must have. | 
 **maxVitaminB1** | **optional.Float32**| The maximum amount of Vitamin B1 in milligrams the recipe can have. | 
 **minVitaminB2** | **optional.Float32**| The minimum amount of Vitamin B2 in milligrams the recipe must have. | 
 **maxVitaminB2** | **optional.Float32**| The maximum amount of Vitamin B2 in milligrams the recipe can have. | 
 **minVitaminB5** | **optional.Float32**| The minimum amount of Vitamin B5 in milligrams the recipe must have. | 
 **maxVitaminB5** | **optional.Float32**| The maximum amount of Vitamin B5 in milligrams the recipe can have. | 
 **minVitaminB3** | **optional.Float32**| The minimum amount of Vitamin B3 in milligrams the recipe must have. | 
 **maxVitaminB3** | **optional.Float32**| The maximum amount of Vitamin B3 in milligrams the recipe can have. | 
 **minVitaminB6** | **optional.Float32**| The minimum amount of Vitamin B6 in milligrams the recipe must have. | 
 **maxVitaminB6** | **optional.Float32**| The maximum amount of Vitamin B6 in milligrams the recipe can have. | 
 **minVitaminB12** | **optional.Float32**| The minimum amount of Vitamin B12 in micrograms the recipe must have. | 
 **maxVitaminB12** | **optional.Float32**| The maximum amount of Vitamin B12 in micrograms the recipe can have. | 
 **minFiber** | **optional.Float32**| The minimum amount of fiber in grams the recipe must have. | 
 **maxFiber** | **optional.Float32**| The maximum amount of fiber in grams the recipe can have. | 
 **minFolate** | **optional.Float32**| The minimum amount of folate in grams the recipe must have. | 
 **maxFolate** | **optional.Float32**| The maximum amount of folate in grams the recipe can have. | 
 **minFolicAcid** | **optional.Float32**| The minimum amount of folic acid in grams the recipe must have. | 
 **maxFolicAcid** | **optional.Float32**| The maximum amount of folic acid in grams the recipe can have. | 
 **minIodine** | **optional.Float32**| The minimum amount of iodine in grams the recipe must have. | 
 **maxIodine** | **optional.Float32**| The maximum amount of iodine in grams the recipe can have. | 
 **minIron** | **optional.Float32**| The minimum amount of iron in milligrams the recipe must have. | 
 **maxIron** | **optional.Float32**| The maximum amount of iron in milligrams the recipe can have. | 
 **minMagnesium** | **optional.Float32**| The minimum amount of magnesium in milligrams the recipe must have. | 
 **maxMagnesium** | **optional.Float32**| The maximum amount of magnesium in milligrams the recipe can have. | 
 **minManganese** | **optional.Float32**| The minimum amount of manganese in milligrams the recipe must have. | 
 **maxManganese** | **optional.Float32**| The maximum amount of manganese in milligrams the recipe can have. | 
 **minPhosphorus** | **optional.Float32**| The minimum amount of phosphorus in milligrams the recipe must have. | 
 **maxPhosphorus** | **optional.Float32**| The maximum amount of phosphorus in milligrams the recipe can have. | 
 **minPotassium** | **optional.Float32**| The minimum amount of potassium in milligrams the recipe must have. | 
 **maxPotassium** | **optional.Float32**| The maximum amount of potassium in milligrams the recipe can have. | 
 **minSelenium** | **optional.Float32**| The minimum amount of selenium in grams the recipe must have. | 
 **maxSelenium** | **optional.Float32**| The maximum amount of selenium in grams the recipe can have. | 
 **minSodium** | **optional.Float32**| The minimum amount of sodium in milligrams the recipe must have. | 
 **maxSodium** | **optional.Float32**| The maximum amount of sodium in milligrams the recipe can have. | 
 **minSugar** | **optional.Float32**| The minimum amount of sugar in grams the recipe must have. | 
 **maxSugar** | **optional.Float32**| The maximum amount of sugar in grams the recipe can have. | 
 **minZinc** | **optional.Float32**| The minimum amount of zinc in milligrams the recipe must have. | 
 **maxZinc** | **optional.Float32**| The maximum amount of zinc in milligrams the recipe can have. | 
 **offset** | **optional.Float32**| The offset number for paging (between 0 and 990). | 
 **number** | **optional.Float32**| The number of expected results (between 1 and 100). | 
 **random** | **optional.Bool**| If true, every request will give you a random set of recipes within the requested limits. | 
 **limitLicense** | **optional.Bool**| Whether the recipes should have an open license that allows display with proper attribution. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchRecipesComplex

> map[string]interface{} SearchRecipesComplex(ctx, query, optional)
Search Recipes Complex

Search through hundreds of thousands of recipes using advanced filtering and ranking. NOTE: This method combines searching by query, by ingredients, and by nutrients into one endpoint.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The (natural language) recipe search query. | 
 **optional** | ***SearchRecipesComplexOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a SearchRecipesComplexOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cuisine** | **optional.String**| The cuisine(s) of the recipes. One or more, comma separated (will be interpreted as &#39;OR&#39;). See a full list of supported cuisines. | 
 **excludeCuisine** | **optional.String**| The cuisine(s) the recipes must not match. One or more, comma separated (will be interpreted as &#39;AND&#39;). See a full list of supported cuisines. | 
 **diet** | **optional.String**| The diet for which the recipes must be suitable. See a full list of supported diets. | 
 **intolerances** | **optional.String**| A comma-separated list of intolerances. All recipes returned must not contain ingredients that are not suitable for people with the intolerances entered. See a full list of supported intolerances. | 
 **equipment** | **optional.String**| The equipment required. Multiple values will be interpreted as &#39;or&#39;. For example, value could be \&quot;blender, frying pan, bowl\&quot;. | 
 **includeIngredients** | **optional.String**| A comma-separated list of ingredients that should/must be used in the recipes. | 
 **excludeIngredients** | **optional.String**| A comma-separated list of ingredients or ingredient types that the recipes must not contain. | 
 **type_** | **optional.String**| The type of recipe. See a full list of supported meal types. | 
 **instructionsRequired** | **optional.Bool**| Whether the recipes must have instructions. | 
 **fillIngredients** | **optional.Bool**| Add information about the used and missing ingredients in each recipe. | 
 **addRecipeInformation** | **optional.Bool**| If set to true, you get more information about the recipes returned. This saves you from needing to call to get recipe information. | 
 **author** | **optional.String**| The username of the recipe author. | 
 **tags** | **optional.String**| User defined tags that have to match. | 
 **titleMatch** | **optional.String**| Enter text that must be found in the title of the recipes. | 
 **maxReadyTime** | **optional.Float32**| The maximum time in minutes it should take to prepare and cook the recipe. | 
 **ignorePantry** | **optional.Bool**| Whether to ignore typical pantry items, such as water, salt, flour, etc. | 
 **sort** | **optional.String**| The strategy to sort recipes by. See a full list of supported sorting options. | 
 **sortDirection** | **optional.String**| The direction in which to sort. Must be either &#39;asc&#39; (ascending) or &#39;desc&#39; (descending). | 
 **minCarbs** | **optional.Float32**| The minimum amount of carbohydrates in grams the recipe must have. | 
 **maxCarbs** | **optional.Float32**| The maximum amount of carbohydrates in grams the recipe can have. | 
 **minProtein** | **optional.Float32**| The minimum amount of protein in grams the recipe must have. | 
 **maxProtein** | **optional.Float32**| The maximum amount of protein in grams the recipe can have. | 
 **minCalories** | **optional.Float32**| The minimum amount of calories the recipe must have. | 
 **maxCalories** | **optional.Float32**| The maximum amount of calories the recipe can have. | 
 **minFat** | **optional.Float32**| The minimum amount of fat in grams the recipe must have. | 
 **maxFat** | **optional.Float32**| The maximum amount of fat in grams the recipe can have. | 
 **minAlcohol** | **optional.Float32**| The minimum amount of alcohol in grams the recipe must have. | 
 **maxAlcohol** | **optional.Float32**| The maximum amount of alcohol in grams the recipe can have. | 
 **minCaffeine** | **optional.Float32**| The minimum amount of caffeine in milligrams the recipe must have. | 
 **maxCaffeine** | **optional.Float32**| The maximum amount of caffeine in milligrams the recipe can have. | 
 **minCopper** | **optional.Float32**| The minimum amount of copper in milligrams the recipe must have. | 
 **maxCopper** | **optional.Float32**| The maximum amount of copper in milligrams the recipe can have. | 
 **minCalcium** | **optional.Float32**| The minimum amount of calcium in milligrams the recipe must have. | 
 **maxCalcium** | **optional.Float32**| The maximum amount of calcium in milligrams the recipe can have. | 
 **minCholine** | **optional.Float32**| The minimum amount of choline in milligrams the recipe must have. | 
 **maxCholine** | **optional.Float32**| The maximum amount of choline in milligrams the recipe can have. | 
 **minCholesterol** | **optional.Float32**| The minimum amount of cholesterol in milligrams the recipe must have. | 
 **maxCholesterol** | **optional.Float32**| The maximum amount of cholesterol in milligrams the recipe can have. | 
 **minFluoride** | **optional.Float32**| The minimum amount of fluoride in milligrams the recipe must have. | 
 **maxFluoride** | **optional.Float32**| The maximum amount of fluoride in milligrams the recipe can have. | 
 **minSaturatedFat** | **optional.Float32**| The minimum amount of saturated fat in grams the recipe must have. | 
 **maxSaturatedFat** | **optional.Float32**| The maximum amount of saturated fat in grams the recipe can have. | 
 **minVitaminA** | **optional.Float32**| The minimum amount of Vitamin A in IU the recipe must have. | 
 **maxVitaminA** | **optional.Float32**| The maximum amount of Vitamin A in IU the recipe can have. | 
 **minVitaminC** | **optional.Float32**| The minimum amount of Vitamin C milligrams the recipe must have. | 
 **maxVitaminC** | **optional.Float32**| The maximum amount of Vitamin C in milligrams the recipe can have. | 
 **minVitaminD** | **optional.Float32**| The minimum amount of Vitamin D in micrograms the recipe must have. | 
 **maxVitaminD** | **optional.Float32**| The maximum amount of Vitamin D in micrograms the recipe can have. | 
 **minVitaminE** | **optional.Float32**| The minimum amount of Vitamin E in milligrams the recipe must have. | 
 **maxVitaminE** | **optional.Float32**| The maximum amount of Vitamin E in milligrams the recipe can have. | 
 **minVitaminK** | **optional.Float32**| The minimum amount of Vitamin K in micrograms the recipe must have. | 
 **maxVitaminK** | **optional.Float32**| The maximum amount of Vitamin K in micrograms the recipe can have. | 
 **minVitaminB1** | **optional.Float32**| The minimum amount of Vitamin B1 in milligrams the recipe must have. | 
 **maxVitaminB1** | **optional.Float32**| The maximum amount of Vitamin B1 in milligrams the recipe can have. | 
 **minVitaminB2** | **optional.Float32**| The minimum amount of Vitamin B2 in milligrams the recipe must have. | 
 **maxVitaminB2** | **optional.Float32**| The maximum amount of Vitamin B2 in milligrams the recipe can have. | 
 **minVitaminB5** | **optional.Float32**| The minimum amount of Vitamin B5 in milligrams the recipe must have. | 
 **maxVitaminB5** | **optional.Float32**| The maximum amount of Vitamin B5 in milligrams the recipe can have. | 
 **minVitaminB3** | **optional.Float32**| The minimum amount of Vitamin B3 in milligrams the recipe must have. | 
 **maxVitaminB3** | **optional.Float32**| The maximum amount of Vitamin B3 in milligrams the recipe can have. | 
 **minVitaminB6** | **optional.Float32**| The minimum amount of Vitamin B6 in milligrams the recipe must have. | 
 **maxVitaminB6** | **optional.Float32**| The maximum amount of Vitamin B6 in milligrams the recipe can have. | 
 **minVitaminB12** | **optional.Float32**| The minimum amount of Vitamin B12 in micrograms the recipe must have. | 
 **maxVitaminB12** | **optional.Float32**| The maximum amount of Vitamin B12 in micrograms the recipe can have. | 
 **minFiber** | **optional.Float32**| The minimum amount of fiber in grams the recipe must have. | 
 **maxFiber** | **optional.Float32**| The maximum amount of fiber in grams the recipe can have. | 
 **minFolate** | **optional.Float32**| The minimum amount of folate in grams the recipe must have. | 
 **maxFolate** | **optional.Float32**| The maximum amount of folate in grams the recipe can have. | 
 **minFolicAcid** | **optional.Float32**| The minimum amount of folic acid in grams the recipe must have. | 
 **maxFolicAcid** | **optional.Float32**| The maximum amount of folic acid in grams the recipe can have. | 
 **minIodine** | **optional.Float32**| The minimum amount of iodine in grams the recipe must have. | 
 **maxIodine** | **optional.Float32**| The maximum amount of iodine in grams the recipe can have. | 
 **minIron** | **optional.Float32**| The minimum amount of iron in milligrams the recipe must have. | 
 **maxIron** | **optional.Float32**| The maximum amount of iron in milligrams the recipe can have. | 
 **minMagnesium** | **optional.Float32**| The minimum amount of magnesium in milligrams the recipe must have. | 
 **maxMagnesium** | **optional.Float32**| The maximum amount of magnesium in milligrams the recipe can have. | 
 **minManganese** | **optional.Float32**| The minimum amount of manganese in milligrams the recipe must have. | 
 **maxManganese** | **optional.Float32**| The maximum amount of manganese in milligrams the recipe can have. | 
 **minPhosphorus** | **optional.Float32**| The minimum amount of phosphorus in milligrams the recipe must have. | 
 **maxPhosphorus** | **optional.Float32**| The maximum amount of phosphorus in milligrams the recipe can have. | 
 **minPotassium** | **optional.Float32**| The minimum amount of potassium in milligrams the recipe must have. | 
 **maxPotassium** | **optional.Float32**| The maximum amount of potassium in milligrams the recipe can have. | 
 **minSelenium** | **optional.Float32**| The minimum amount of selenium in grams the recipe must have. | 
 **maxSelenium** | **optional.Float32**| The maximum amount of selenium in grams the recipe can have. | 
 **minSodium** | **optional.Float32**| The minimum amount of sodium in milligrams the recipe must have. | 
 **maxSodium** | **optional.Float32**| The maximum amount of sodium in milligrams the recipe can have. | 
 **minSugar** | **optional.Float32**| The minimum amount of sugar in grams the recipe must have. | 
 **maxSugar** | **optional.Float32**| The maximum amount of sugar in grams the recipe can have. | 
 **minZinc** | **optional.Float32**| The minimum amount of zinc in milligrams the recipe must have. | 
 **maxZinc** | **optional.Float32**| The maximum amount of zinc in milligrams the recipe can have. | 
 **offset** | **optional.Float32**| The offset number for paging (between 0 and 990). | 
 **number** | **optional.Float32**| The number of expected results (between 1 and 10). | 
 **limitLicense** | **optional.Bool**| Whether the recipes should have an open license that allows display with proper attribution. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchSiteContent

> map[string]interface{} SearchSiteContent(ctx, query)
Search Site Content

Search spoonacular's site content. You'll be able to find everything that you could also find using the search suggestions on spoonacular.com. This is a suggest API so you can send partial strings as queries.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**query** | **string**| The query to search for. You can also use partial queries such as \&quot;spagh\&quot; to already find spaghetti recipes, articles, grocery products, and other content. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SummarizeRecipe

> map[string]interface{} SummarizeRecipe(ctx, id)
Summarize Recipe

Automatically generate a short description that summarizes key information about the recipe.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TalkToChatbot

> map[string]interface{} TalkToChatbot(ctx, text, optional)
Talk to Chatbot

This endpoint can be used to have a conversation about food with the spoonacular chatbot. Use the \"Get Conversation Suggests\" endpoint to show your user what he or she can say.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**text** | **string**| The request / question / answer from the user to the chatbot. | 
 **optional** | ***TalkToChatbotOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a TalkToChatbotOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **contextId** | **optional.String**| An arbitrary globally unique id for your conversation. The conversation can contain states so you should pass your context id if you want the bot to be able to remember the conversation. | 

### Return type

[**map[string]interface{}**](map[string]interface{}.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeEquipment

> string VisualizeEquipment(ctx, ingredientList, servings, optional)
Visualize Equipment

Visualize the equipment used to make a recipe.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientList** | **string**| The ingredient list of the recipe, one ingredient per line. | 
**servings** | **float32**| The number of servings. | 
 **optional** | ***VisualizeEquipmentOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeEquipmentOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **view** | **optional.String**| How to visualize the equipment, either \\\&quot;grid\\\&quot; or \\\&quot;list\\\&quot;. | 
 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 
 **showBacklink** | **optional.Bool**| Whether to show a backlink to spoonacular. If set false, this call counts against your quota. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeIngredients

> string VisualizeIngredients(ctx, ingredientList, servings, optional)
Visualize Ingredients

Visualize ingredients of a recipe.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientList** | **string**| The ingredient list of the recipe, one ingredient per line. | 
**servings** | **float32**| The number of servings. | 
 **optional** | ***VisualizeIngredientsOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeIngredientsOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **measure** | **optional.String**| The original system of measurement, either \\\&quot;metric\\\&quot; or \\\&quot;us\\\&quot;. | 
 **view** | **optional.String**| How to visualize the ingredients, either \\\&quot;grid\\\&quot; or \\\&quot;list\\\&quot;. | 
 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 
 **showBacklink** | **optional.Bool**| Whether to show a backlink to spoonacular. If set false, this call counts against your quota. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeMenuItemNutritionByID

> string VisualizeMenuItemNutritionByID(ctx, id, optional)
Visualize Menu Item Nutrition by ID

Visualize a menu item's nutritional information as HTML including CSS.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The menu item id. | 
 **optional** | ***VisualizeMenuItemNutritionByIDOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeMenuItemNutritionByIDOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizePriceBreakdown

> string VisualizePriceBreakdown(ctx, ingredientList, servings, optional)
Visualize Price Breakdown

Visualize the price breakdown of a recipe.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientList** | **string**| The ingredient list of the recipe, one ingredient per line. | 
**servings** | **float32**| The number of servings. | 
 **optional** | ***VisualizePriceBreakdownOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizePriceBreakdownOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **mode** | **optional.Float32**| The mode in which the widget should be delivered. 1 &#x3D; separate views (compact), 2 &#x3D; all in one view (full). | 
 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 
 **showBacklink** | **optional.Bool**| Whether to show a backlink to spoonacular. If set false, this call counts against your quota. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeProductNutritionByID

> string VisualizeProductNutritionByID(ctx, id, optional)
Visualize Product Nutrition by ID

Visualize a product's nutritional information as HTML including CSS.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The id of the product. | 
 **optional** | ***VisualizeProductNutritionByIDOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeProductNutritionByIDOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeRecipeEquipmentByID

> string VisualizeRecipeEquipmentByID(ctx, id, optional)
Visualize Recipe Equipment by ID

Visualize a recipe's equipment list.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 
 **optional** | ***VisualizeRecipeEquipmentByIDOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeRecipeEquipmentByIDOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeRecipeIngredientsByID

> string VisualizeRecipeIngredientsByID(ctx, id, optional)
Visualize Recipe Ingredients by ID

Visualize a recipe's ingredient list.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 
 **optional** | ***VisualizeRecipeIngredientsByIDOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeRecipeIngredientsByIDOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeRecipeNutrition

> string VisualizeRecipeNutrition(ctx, ingredientList, servings, optional)
Visualize Recipe Nutrition

Visualize a recipe's nutritional information as HTML including CSS

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ingredientList** | **string**| The ingredient list of the recipe, one ingredient per line. | 
**servings** | **float32**| The number of servings. | 
 **optional** | ***VisualizeRecipeNutritionOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeRecipeNutritionOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 
 **showBacklink** | **optional.Bool**| Whether to show a backlink to spoonacular. If set false, this call counts against your quota. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeRecipeNutritionByID

> string VisualizeRecipeNutritionByID(ctx, id, optional)
Visualize Recipe Nutrition by ID

Visualize a recipe's nutritional information as HTML including CSS.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 
 **optional** | ***VisualizeRecipeNutritionByIDOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeRecipeNutritionByIDOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VisualizeRecipePriceBreakdownByID

> string VisualizeRecipePriceBreakdownByID(ctx, id, optional)
Visualize Recipe Price Breakdown by ID

Visualize a recipe's price breakdown.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **float32**| The recipe id. | 
 **optional** | ***VisualizeRecipePriceBreakdownByIDOpts** | optional parameters | nil if no parameters

### Optional Parameters

Optional parameters are passed through a pointer to a VisualizeRecipePriceBreakdownByIDOpts struct


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultCss** | **optional.Bool**| Whether the default CSS should be added to the response. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


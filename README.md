# House prediction web app
----------------------------

This project intention to Predict different House type Prices in different states in AUS. This Model helps to Real estates to quickly predict house prices in AUS.
 
## Quick start


1. Add ``webapp1``,``webapp2``,``webapp3`` to your INSTALLED_APPS setting like this::
    
    INSTALLED_APPS = [
    
     			'Deployment',
                       'widget_tweaks',
                       'crispy_forms',  
   	            ]
    

2. Include the every app URLconf in your project urls.py like this
   ``` bash
	urlpatterns = [
			path('admin/', admin.site.urls),
			path('',include('Deployment.urls')),
		      ]
    ```

3. Run ``python manage.py migrate`` to create the ``Deployment``  models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a those three apps (you'll need the Admin app enabled).
   - create a admin 
   	-- python manage.py createsuperuser

5. Visit http://127.0.0.1:8000/ for homepage
6. Detail documentation [click here](https://github.com/Nagababu91768/house-price-prediction-ml-app/blob/master/README.md)

## License
[MIT](https://choosealicense.com/licenses/mit/)

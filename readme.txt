{% url 'contact' %} this is used to render to the html page 

    class Meta:
        ordering = ('name',)
        verbos_name_plural = 'Categories' (this class is defined to update the string name in the database, and also getting the names in order )

{{form.as_p}}  this one is used to create a signup template where it shows what to fill in as for our username password and many more
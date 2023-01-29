# blango

Starting point for the Advanced Django course. This is the equivalent of the following command:

```bash
$ django-admin.py startproject blango
```

Topics covered in this project:
1. Generic relationships
- Identify limitations of not using generic relationships
- Dynamically access models using the contenttypes
framework
- Create generic relationships between different models
- Use GenericRelation for reverse queries
- Create the Comment model with a generic relationship to
the Post model
3. Bootstrap HTML framework
4. Custom filters and producing safe HTML
- Use built-in filters in a Django template
- Create custom template tags for the posts
- Create a custom filter and add it to a template
- Render text safe to increase the security of the blog
- Pass an argument to a filter
5. Cutsom template tags
- Identify why custom template tags can be better than
filters
- Create a simple tag
- Add context to a custom template tag
- Use a template inside another template with inclusion
tags
- Identify when to use an advanced template tag

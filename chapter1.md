# React Notes



The idea of creating a base class is to reduce boiler plate code in your backbone model or views.

Lets create a base class for a Backbone View render method.

`Var BaseView = Backbone.View.extend({   
                render: function()  
                {  
                  var tpl = _.template(this.template),    
                  data = (this.model) ? this.model.toJSON(): {},   
                  html = tpl(data);   
                  this.$el.html(html);   
                  return this;  
                  }  
                  })`


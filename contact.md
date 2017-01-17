---
layout: page-no-recent
title: Contacto
permalink: /contacto/
---


Por consultas, sugerencias y demás, por favor dejanos un mensaje.

<form id="contact-form" class="form-horizontal" action="https://getsimpleform.com/messages?form_api_token=b6366dffeb23c6592fcd9e990f0ec919" method="POST" enctype="multipart/form-data">
       <fieldset>
       
            <div class="form-group">
                <label class="col-lg-2 control-label" for="name">Nombre:</label>
                <div class="col-lg-10">
                <input required type="text" placeholder="Tu nombre" id="name" class="form-control" name="name" tabindex="1"/>
                </div>
            </div>
            <div class="form-group">
                <label class="col-lg-2 control-label" for="email">Email:</label>
                <div class="col-lg-10">
                <input required type="email" placeholder="Tu dirección de correo electrónico" id="email" class="form-control" name="email" tabindex="2"/>
                </div>
            </div>
             <div class="form-group">
               <label class="col-lg-2 control-label" for="reason">Motivo:</label>
               <div class="col-lg-10">
                   <select class="form-control" id="reason" placeholder="1" name="reason">
                        <option>Dudas</option>
                        <option>Quiero formar parte</option>
                        <option>Tengo una donación</option>
                        <option>Necesito una Donación</option>
                        <option>Invitación a participar</option>
                        <option>Sugerencias sobre redes</option>
                        <option>Consulta sobre actividades</option>
                        <option>Tu opinion nos importa</option>
                        <option>Ayudas económicas</option>
                        <option>Otros</option>                     
                   </select>
               </div>
             </div>
            <div class="form-group">
                <label class="col-lg-2 control-label" for="message">Mensaje:</label>
                <div class="col-lg-10">
                <textarea required class="contact-textarea" placeholder="Tu mensaje" class="form-control" rows="4" id="message" name="message" tabindex="3"></textarea>
                </div>
            </div>
            
           <div class="form-group"> 
           <div class="col-lg-10 col-lg-offset-2">  
         <input type="submit" class="btn btn-primary" value="Enviar" id="submit"/>
         </div>
         </div>
        <input type="hidden" name='redirect_to' value="http://{{site.url}}/gracias"/>
    </fieldset>  
</form>
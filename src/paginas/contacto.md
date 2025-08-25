---
title: "Contacto"
meta_title: "Contacto | HOW – HandsOn Warehouse"
meta_description: "Solicita tu diagnóstico inicial. Formulario con RGPD."
layout: "layouts/base.njk"
permalink: "/contacto/index.html"
---
# Contacto

Rellena el formulario y te responderemos en menos de 1-2 días laborables.

<form name="contacto-how" method="POST" data-netlify="true" netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="contacto-how" />
  <p style="display:none"><label>Si eres humano, deja esto vacío: <input name="bot-field" /></label></p>
  <p><label>Nombre<br><input type="text" name="nombre" required></label></p>
  <p><label>Empresa<br><input type="text" name="empresa" required></label></p>
  <p><label>Email<br><input type="email" name="email" required></label></p>
  <p><label>Mensaje<br><textarea name="mensaje" required></textarea></label></p>
  <p><label><input type="checkbox" name="rgpd" required> He leído y acepto la <a href="/legal/privacidad/">Política de privacidad</a></label></p>
  <p><button type="submit">Enviar</button></p>
</form>

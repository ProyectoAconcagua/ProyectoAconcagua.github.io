.. title: Modulos
.. slug: modulos
.. date: 2014-07-28 12:23:14 UTC-03:00
.. tags: modulos
.. link: 
.. description: Proyecto Aconcagua - Modulos
.. template: post_colorbox.tmpl


.. raw:: html

    <div class="section row" id="modules"> 

      <div class="col-md-6" id="point_of_sale">
        <div><h1>Punto de Venta</h1></div><div class="lead">l10n_ar_point_of_sale</div>
        <span style="float: right;">
          <a type="button" href="https://github.com/ProyectoAconcagua/l10n_ar_point_of_sale_v7/issues" target="new" class="btn btn-warning btn-sm">Reportar Bug</a>
        </span>
        <ul class="nav nav-tabs" style="margin-bottom: 15px;">
          <li class="active"><a href="#mod1_desc" data-toggle="tab">Descripci&oacute;n</a></li>
          <li class=""><a href="#mod1_screenshot" data-toggle="tab">Capturas</a></li>
        </ul>
        <div id="postabcontent" class="tab-content" style="height: 300px;">
          <div class="tab-pane fade active in" id="mod1_desc">
            <p>El módulo de punto de venta introduce conceptos básicos de la contabilidad Argentina, tales como <strong>denominación, punto de venta, tipo de factura, tipo de comprobante, etc.</strong>.</p>
            <p>Contiene la lógica necesaria para:</p>
            <ul>
              <li>Asignar la denominación correspondiente según las <em>posiciones fiscales</em></li>
              <li>Calcular el número de comprobante según <em>tipo, denominación y punto de venta</em></li>
              <li>Realizar <em>chequeos fiscales</em> previos a validar la factura, como por ejemplo, que coincidan la posición fiscal y la denominación del comprobante.</li>
              <li>Incluir el concepto de notas de débito sin afectar demasiado el código de <em>OpenERP/Odoo</em></li>
            </ul>
            <ul class="list-inline">
              <li>
                <iframe src="http://www.ghbtns.com/github-btn.html?user=ProyectoAconcagua&repo=l10n_ar_point_of_sale_v7&type=watch&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="110" height="20"></iframe>
              </li>
              <li>
                <iframe src="http://www.ghbtns.com/github-btn.html?user=ProyectoAconcagua&repo=l10n_ar_point_of_sale_v7&type=fork&count=true" frameborder="0" scrolling="0" width="95" height="20"></iframe>
              </li>
              <li>
                  <a href="https://twitter.com/share" class="twitter-share-button" data-url="http://bit.ly/aconcag_pos" data-lang="en" data-text="Módulo de Punto de venta para #Odoo #OpenERP #ProyectoAconcagua">Tweet</a>
              </li>
          </ul>
          </div>
          <div class="tab-pane fade" id="mod1_screenshot">
            <div class="row" id="tabscreenshots">
              <div class="col-md-6" >
                <h3>Capturas de pantalla</h3>
                <p><a class="pos" href="/galleries/modulos/pos1.png" title="Pos1">Configuración de puntos de venta</a></p>
                <p><a class="pos" href="/galleries/modulos/pos2.png" title="Pos2">Comprobantes con denominación, punto de venta y número</a></p>
                <p><a class="pos" href="/galleries/modulos/pos3.png" title="Pos3">Configuración de Denominaciones</a></p>
                <p><a class="pos" href="/galleries/modulos/pos4.png" title="Pos4">Configuración de Posiciones Fiscales</a></p>
              </div>
              <div class="col-md-6" >
                <h3>Videotutoriales</h3>
                <p><a class='youtube' href="https://www.youtube.com/embed/lojiQP9nyIw?rel=0&amp;wmode=transparent">Denominaciones, Posición Fiscal y Puntos de Venta</a></p>
                <p><a class='youtube' href="https://www.youtube.com/embed/xa1Ie8-dQ9c?rel=0&amp;wmode=transparent">Creación de Clientes</a></p>
                <p><a class='youtube' href="https://www.youtube.com/embed/4ROxsEAl8_U?rel=0&amp;wmode=transparent">Creación de Proveedores</a></p>
              </div>
            </div>
          </div>
        </div> 
      </div> 

      <div class="col-md-6" id="payment">
        <div><h1>Cobros y pagos</h1></div><div class="lead">l10n_ar_account_payment</div>
        <span style="float: right;">
          <a type="button" href="https://github.com/ProyectoAconcagua/l10n_ar_account_payment_v7/issues" target="new" class="btn btn-warning btn-sm">Reportar Bug</a>
        </span>
        <ul class="nav nav-tabs" style="margin-bottom: 15px;">
          <li class="active"><a href="#mod2_desc" data-toggle="tab">Descripci&oacute;n</a></li>
          <li class=""><a href="#mod2_screenshot" data-toggle="tab">Capturas</a></li>
        </ul>
        <div id="paytabcontent" class="tab-content" style="height: 300px;">
          <div class="tab-pane fade active in" id="mod2_desc">
            <p>El módulo de cobros y pagos extiende el módulo <strong>account_voucher</strong> para agregarle <em>varias formas de cobros/pagos</em>. Soporta multimoneda.</p>
            <p>Además, agrega varios <em>hooks</em> para extender la funcionalidad en los comprobantes de cobros y pagos, por lo tanto, sirve de base para los módulos de cheques y retenciones.</p>
            <p>Contiene la lógica necesaria para:</p>
            <ul>
              <li>Configurar distintas formas de cobro y de pago por separado.</li>
              <li>Asignar una cuenta contable a cada forma de cobro/pago.</li>
              <li>Incluir de forma automática las formas de cobro/pago según sea para cobro o pago y tipo de moneda.</li>
              <li>Crear asientos contables correspondientes según la configuración efectuada.</li>
            </ul>
            <ul class="list-inline">
              <li>
                <iframe src="http://www.ghbtns.com/github-btn.html?user=ProyectoAconcagua&repo=l10n_ar_account_payment_v7&type=watch&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="110" height="20"></iframe>
              </li>
              <li>
                <iframe src="http://www.ghbtns.com/github-btn.html?user=ProyectoAconcagua&repo=l10n_ar_account_payment_v7&type=fork&count=true" frameborder="0" scrolling="0" width="95" height="20"></iframe>
              </li>
              <li>
                  <a href="https://twitter.com/share" class="twitter-share-button" data-url="http://bit.ly/aconcag_pay" data-lang="en" data-text="Módulo de Cobros y pagos para #Odoo #OpenERP #ProyectoAconcagua">Tweet</a>
              </li>
          </ul>
          </div>
          <div class="tab-pane fade" id="mod2_screenshot">
            <div class="row" id="tabscreenshots">
              <div class="col-md-6" >
                <h3>Capturas de pantalla</h3>
                <p><a class="pay" href="/galleries/modulos/pay1.png" title="pay1">Configuración de modos de cobro/pago</a></p>
                <p><a class="pay" href="/galleries/modulos/pay2.png" title="pay2">Cobro realizado a un cliente</a></p>
                <p><a class="pay" href="/galleries/modulos/pay3.png" title="pay3">Pago realizado a un proveedor</a></p>
              </div>
              <div class="col-md-6" >
                <h3>Videotutoriales</h3>
                <p><a class='youtube' href="https://www.youtube.com/embed/6eYTi9ZoNRA?rel=0&amp;wmode=transparent">Configuración de Modo de Pagos y Cobros</a></p>
              </div>
            </div>
          </div>
        </div> 
      </div>


   </div>


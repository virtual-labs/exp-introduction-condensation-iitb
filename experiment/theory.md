<div class="theory-wrap">

  <!-- ═══════════════════════════════════════════════════════ TITLE -->
  <h1>Condensation</h1>

  <p>
    When phase change from vapor to liquid occurs, by giving out the latent heat to the
    surface, which is at a temperature lower than the saturation temperature, the process
    is called <strong>'Condensation'</strong>.
  </p>

  <hr>

  <!-- ═══════════════════════════════════════════════════ TYPES -->
  <h2>Types of Condensation</h2>

  <p>Condensation of vapor may take place in two different ways.</p>

  <!-- ── 1. Filmwise ── -->
  <h3>1. Filmwise Condensation</h3>

  <p>
    In this type, the condensate forms a film over the surface. The surface gets wet.
    Under the gravitational force, the condensate flows down the surface. The thickness
    of the film increases in downward direction. Due to low thermal conductivity of the
    condensate, the film offers high resistance to the heat flow. Hence, in this type,
    we get very low rates of condensation.
  </p>

  <div class="fig-wrap center">
    <img src="./images/th1.png" style="width: 520px;" alt="Fig 10.1 : Filmwise and Dropwise Condensation">
    <span class="fig-caption">Fig 10.1 : Filmwise and Dropwise Condensation</span>
  </div>

  <!-- ── 2. Dropwise ── -->
  <h3>2. Dropwise Condensation</h3>

  <p>
    In this type, the condensate forms droplets on the surface. The droplets gets
    coalesced with the neighboring droplet and roll down the surface due to
    gravitational force. (Ref. Fig. 10.1 b)
  </p>
  <p>
    The experimental results show that in dropwise condensation, the heat transfer rate
    is much higher than that in filmwise condensation. This is because, in dropwise
    condensation, the surface always remains in direct contact with the vapor.
  </p>
  <p>
    That is why, it is always desirable to have dropwise condensation. But practically
    it is very difficult to achieve drop condensation for a long period of time. This is
    because once the surface gets wet, it results in film condensation. Different
    additives are found to maintain and prolong dropwise condensation. These additives
    are known as condensation promoters. Oleic acid is one of the widely used promoter.
    Highly polished surfaces also practice dropwise condensation. In order to improve
    the smoothness of the surface, they are coated with chromium.
  </p>
  <p>
    Still while designing any equipment, it is assumed that only film condensation
    occurs in practice.
  </p>

  <hr>

  <!-- ═════════════════════════════════════════ NUSSELT THEORY -->
  <h2>Film Condensation on Vertical Plate / Nusselt's Theory of Film Condensation</h2>

  <p>While analyzing the case of condensation over a plate, following assumptions are made:</p>

  <ol>
    <li>The flow of condensate in the film is laminar.</li>
    <li>The fluid properties are constant.</li>
    <li>The liquid vapor interface is at saturation temperature.</li>
    <li>There is no shear stress or thermal resistance at liquid-vapor interface.</li>
    <li>Heat transfer across film is due to pure conduction and the temperature distribution is linear.</li>
  </ol>

  <p>
    Let us consider an infinitesimal thin section of the plate at distance Z and of
    thickness dz. From this section consider a differential control volume at distance
    x from the plate and of thickness dx.
  </p>

  <!-- Fig 10.2 and 10.3 side by side -->
  <div class="fig-row">
    <div class="fig-item">
      <img src="./images/th2.png" style="width: 340px;" alt="Fig 10.2">
      <span class="fig-caption">Fig. 10.2 : Film of condensate on a vertical plate</span>
    </div>
    <div class="fig-item">
      <img src="./images/th3.png" style="width: 320px;" alt="Fig 10.3">
      <span class="fig-caption">Fig. 10.3 : Force equilibrium of the differential element</span>
    </div>
  </div>

  <p>Let the plate be having unit width.</p>

  <p>Let:</p>
  <ul class="var-list">
    <li><span style='display: inline-block;' >$$ T_w $$ </span> &nbsp;— Temperature of the plate</li>
    <li><span style='display: inline-block;'>$$ T_{sat} $$ </span> — Temperature at the interface between film and vapor</li>
    <li><span style='display: inline-block;'>$$ V $$ </span> &nbsp;&nbsp;— Velocity of elemental volume in z direction</li>
    <li><span style='display: inline-block;'> $$\delta$$ </span> &nbsp;— Film thickness at distance Z from the top edge</li>
  </ul>

  <p>Fig. 10.3 shows the shear and gravitational forces acting on differential element.</p>

  <p>where</p>

  <div class="eq-block">$$W = \rho \times (dx \times dz \times 1) \times g = \rho \, g \, dx \, dz$$</div>
  <div class="eq-block">$$F_{s_x} = \mu \frac{dV}{dx} \, dz$$</div>
  <div class="eq-block">$$F_{s_{(x+dx)}} = \mu \left[ \frac{dV}{dx} + \frac{d}{dx}\left(\frac{dV}{dx}\right) dx \right] dz$$</div>

  <p>Hence, we can write the Force balance equation as,</p>

  <div class="eq-block">$$F_{s_{(x+dx)}} - F_{s_x} + W = 0$$</div>
  <div class="eq-block">$$\mu \frac{dV}{dx} \, dz + \mu \frac{d^2V}{dx^2} \, dx \, dz - \mu \frac{dV}{dx} \, dz + \rho \, g \, dx \, dz = 0$$</div>
  <div class="eq-block">$$\therefore \quad \mu \frac{d^2V}{dx^2} \, dx \, dz + \rho g \, dx \, dz = 0$$</div>
  <div class="eq-block">$$\therefore \quad \frac{d^2V}{dx^2} = -\frac{\rho g}{\mu} \tag{1}$$</div>

  <p>Integrating we get,</p>

  <div class="eq-block">$$\frac{dV}{dx} = -\frac{\rho g}{\mu} x + C_1 \tag{2}$$</div>
  <div class="eq-block">$$V = -\frac{\rho \, g x^2}{2\mu} + C_1 x + C_2 \tag{3}$$</div>

  <p>Boundary conditions are:</p>

  <div class="bc-row">
    <span>(i) &nbsp; at <span style='display: inline-block;'> $$ x = 0,\ V = 0 $$ </span></span>
    <span>(ii) &nbsp; at <span style='display: inline-block;'> $$ x = \delta,\ \dfrac{dV}{dx} = 0 $$ </span></span>
  </div>

  <p>From boundary condition (i), and equation (3), we get,</p>
  <div class="eq-block">$$C_2 = 0$$</div>

  <p>From boundary condition (ii) and equation (2), we get,</p>
  <div class="eq-block">$$C_1 = \frac{\rho g \delta}{\mu}$$</div>

  <p>Substituting in eqn. (3), we get,</p>
  <div class="eq-block">$$V = \frac{\rho g}{\mu} \left( x\delta - \frac{x^2}{2} \right) \tag{10.1}$$</div>

  <p>The mass flow rate through the differential control volume is,</p>
  <div class="eq-block">$$\dot{m} = \rho \times A \times V = \rho \times (dx \times 1) \times V = \rho \, dx \, V$$</div>
  <div class="eq-block">$$\therefore \quad \dot{m} = \frac{\rho^2 g}{\mu} \left( x\delta - \frac{x^2}{2} \right) dx$$</div>

  <p>
    The mass flow rate of liquid through the section at distance Z can be obtained by
    integrating <span style='display: inline-block;'> $$(\dot{m})$$ </span> over the film thickness <span style='display: inline-block;'> $$\delta$$. </span> Integrating we get,
  </p>
  <div class="eq-block">$$\dot{m} = \frac{\rho^2 g}{\mu} \int_0^{\delta} \left( x\delta - \frac{x^2}{2} \right) dx = \frac{\rho^2 g}{\mu} \left( \frac{\delta x^2}{2} - \frac{x^3}{6} \right)_0^{\delta}$$</div>
  <div class="eq-block">$$\therefore \quad \dot{m} = \frac{\rho^2 \, g \, \delta^3}{3\mu} \tag{10.2}$$</div>

  <p>
    The rate of condensation (rate of change of mass) at this section is
    <span style='display: inline-block;'> $$\dfrac{d\dot{m}}{d\delta}$$ </span>. It is obtained by differentiating the equation 10.2
    obtained for mass flow rate w.r.t. <span style='display: inline-block;' > $$\delta$$ </span>.
  </p>
  <div class="eq-block">$$\frac{d\dot{m}}{d\delta} = \frac{\rho^2 \, g \, \delta^2}{\mu}$$</div>
  <div class="eq-block">$$\therefore \quad d\dot{m} = \frac{\rho^2 \, g \, \delta^2}{\mu} \, d\delta \tag{4}$$</div>

  <!-- Fig 10.4 -->
  <div class="fig-wrap center">
    <img src="./images/th4.png" style="width: 360px;" alt="Fig 10.4 : Energy balance along the strip">
    <span class="fig-caption">Fig. 10.4 : Energy balance along the strip</span>
  </div>

  <p>
    From energy balance diagram at the interface between liquid and vapor, we can write,
  </p>
  <p>
    Rate of heat released due to condensation of mass <span style='display: inline-block;'> $$d\dot{m}$$ </span> = Rate of heat
    conducted through the film
  </p>

  <div class="eq-block">$$\therefore \quad q = \lambda \times d\dot{m} = \frac{KA}{b}(T_1 - T_2)$$</div>
  <div class="eq-block">$$\therefore \quad \lambda \, d\dot{m} = \frac{K\,(dz \times 1)\,(T_{sat} - T_w)}{\delta} \tag{5}$$</div>

  <p>Substituting value of <span style='display: inline-block;'> $$d\dot{m}$$ </span> from equation (4), we get,</p>
  <div class="eq-block">$$\therefore \quad \frac{\lambda \, \rho^2 \, g \, \delta^2}{\mu} \, d\delta = \frac{K\,(T_{sat} - T_w)\,dz}{\delta}$$</div>

  <p>Separating the variables, we get,</p>
  <div class="eq-block">$$\delta^3 \, d\delta = \frac{K\,(T_{sat} - T_w)\,\mu}{\lambda \, \rho^2 g} \, dz$$</div>

  <p>Integrating we get,</p>
  <div class="eq-block">$$\frac{\delta^4}{4} = \frac{K\,(T_{sat} - T_w)\,\mu}{\lambda \rho^2 g} \times Z$$</div>
  <div class="eq-block">$$\therefore \quad \delta = \left( \frac{4K\,(T_{sat} - T_w)\,\mu\,Z}{\lambda \rho^2 g} \right)^{1/4} \tag{10.3}$$</div>

  <p>
    At the elementary section of wall, steady state equation can be written as,
  </p>
  <p>Rate of conduction through the film = Rate of convection from the film and the wall</p>

  <div class="eq-block">$$\therefore \quad \frac{KA\,(T_1 - T_2)}{b} = hA\,(T_1 - T_2)$$</div>
  <div class="eq-block">$$\therefore \quad \frac{K \times (dz \times 1)(T_{sat} - T_w)}{\delta} = h_z\,(dz \times 1)\,(T_{sat} - T_w)$$</div>
  <div class="eq-block">$$\therefore \quad h_z = \frac{K}{\delta}$$</div>

  <p>Where <span style='display: inline-block;'> $$ h_z $$ </span> is local heat transfer coefficient.</p>
  <p>Substituting in equation (10.3), we get,</p>
  <div class="eq-block">$$h_z = \left( \frac{\lambda \, \rho^2 \, g \, K^3}{4\,(T_{sat} - T_w)\,\mu\,Z} \right)^{1/4} \tag{10.4}$$</div>

  <p>
    Let <span style='display: inline-block;'> $$h_{av}$$ </span> be the heat transfer coefficient over entire length of the plate.
    We can write,
  </p>
  <div class="eq-block">$$h_{av} = \frac{1}{L} \int_0^L h_z \, dz$$</div>
  <div class="eq-block">$$\therefore \quad h_{av} = \frac{1}{L} \left( \frac{\lambda \, \rho^2 \, g \, K^3}{4\,(T_{sat} - T_w)\,\mu} \right)^{1/4} \int_0^L \frac{dz}{Z^{1/4}}$$</div>
  <div class="eq-block">$$\therefore \quad h_{av} = \frac{1}{L} \left( \frac{\lambda \, \rho^2 \, g \, K^3}{4\,(T_{sat} - T_w)\,\mu} \right)^{1/4} \left( \frac{Z^{3/4}}{3/4} \right)_0^L$$</div>
  <div class="eq-block">$$\therefore \quad h_{av} = \frac{4}{3} \left( \frac{\lambda \, \rho^2 \, g \, K^3}{4\,(T_{sat} - T_w)\,\mu} \right)^{1/4} \frac{L^{3/4}}{L}$$</div>
  <div class="eq-block">$$\therefore \quad h_{av} = \frac{4}{3} \left( \frac{\lambda \, \rho^2 \, g \, K^3}{4\,(T_{sat} - T_w)\,\mu L} \right)^{1/4} \tag{10.5}$$</div>

  <p>
    If <span style='display: inline-block;'> $$h_L$$ </span> is heat transfer coefficient at <span style='display: inline-block;'> $$z = L$$ </span>, we can write from equation
    (10.4) and (10.5):
  </p>
  <div class="eq-block">$$h_{av} = \frac{4}{3}\, h_L \tag{10.6}$$</div>

  <p>Rearranging the terms of equation (10.5), we get,</p>
  <div class="eq-block">$$h_{av} = \frac{4}{3} \times \frac{1}{4^{1/4}} \left( \frac{\lambda \, \rho^2 \, g \, K^3}{(T_{sat} - T_w)\,\mu L} \right)^{1/4}$$</div>
  <div class="eq-block">$$\therefore \quad h_{av} = 0.943 \left( \frac{\lambda \, \rho^2 \, g \, K^3}{(T_{sat} - T_w)\,\mu L} \right)^{1/4} \tag{10.7}$$</div>

  <hr>

  <!-- ═══════════════════════════════════════ HORIZONTAL TUBES -->
  <h2>Condensation on Horizontal Tubes</h2>

  <p>
    Nusselt's correlation for the H.T. coefficient for condensation over a bank of
    horizontal tubes is,
  </p>
  <div class="eq-block">$$h = 0.725 \left( \frac{\lambda \, \rho^2 \, g \, K^3}{(T_{sat} - T_w)\,\mu D n} \right)^{1/4} \tag{10.8}$$</div>

  <p>where &nbsp;  n — Number of tubes in a horizontal tube bank.</p>

  <p>
    This formula is also applicable when condensation takes place on inner surface of
    cylinder, provided the length of pipe is short and the condensate film does not
    separate from the surface.
  </p>

  <hr>

  <!-- ═══════════════════════════════════ SUPERHEATED VAPOR -->
  <h2>Condensation of Super Heated Vapor</h2>

  <p>
    When the vapor is super heated, the heat required to be extracted from it in order
    to obtain phase change is:
  </p>
  <div class="eq-block">$$Q = \lambda + C_p\,(T_{sup} - T_{sat})$$</div>

  <p>
    Hence the correlation is obtained by substituting
    <span style='display: inline-block;'> $$[\lambda + C_p\,(T_{sup} - T_{sat})]$$ </span> for <span style='display: inline-block;'> $$\lambda$$ </span> in eqn. (10.7):
  </p>
  <div class="eq-block">$$h_{av} = 0.943 \left( \frac{[\lambda + C_p\,(T_{sup} - T_{sat})]\,\rho^2 g\,K^3}{(T_{sat} - T_w)\,\mu\,L} \right)^{1/4} \tag{10.9}$$</div>

  <hr>

  <!-- ═══════════════════════════════════ INCLINED PLATE -->
  <h2>Condensation over Inclined Plate</h2>

  <p>
    The equation (10.7) which is developed for the case of condensation over a vertical
    surface gets modified if the plate is inclined. Now it becomes,
  </p>
  <div class="eq-block">$$h_{av} = 0.943 \left( \frac{\lambda \, \rho^2 \, g \, K^3 \cos\alpha}{(T_{sat} - T_w)\,\mu L} \right)^{1/4} \tag{10.10}$$</div>

  <p>Where <span style='display: inline-block;'> $$\alpha$$ </span> is the angle made by the plate with vertical plane.</p>

  <div class="note">
    <strong>Note:</strong> The accuracy of all the above correlation increases if the
    term in the numerator <span style='display: inline-block;'> $$\rho^2$$ </span> is replaced by the term <span style='display: inline-block;'> $$\rho(\rho - \rho_v)$$ </span>, where
    <ul>
      <li><span style='display: inline-block;'> $$\rho$$ </span> &nbsp;— Density of the saturated liquid</li>
      <li> <span style='display: inline-block;'> $$\rho_v$$ </span> — Density of the saturated vapor</li>
    </ul>
  </div>

</div><!-- /.theory-wrap -->

<script type="text/javascript" id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"> </script>
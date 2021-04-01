<template>
  <AppProject name="Cycles" author="Felix Deiters">
    <template #header>
      <div>
        <p>
          The way we build is a major driver of the climate crisis. This
          realisation has spawned the creation of sophisticated tools to
          quantify the impact of the built environment on our habitat. Yet, the
          emergence of these frameworks does not seem to have had a meaningful
          impact on the paradigms of the architecture that goes up around us
          every day. These buildings still seem to air a mournful longing for an
          ill-conceived Modernism when the challenges of the present call for
          new approaches. Why does this disconnect exist?
        </p>
        <p>
          I think that instruments such as Life-Cycle Assessments fail to make
          their mark mainly because (a) they enter the picture too late in the
          design process, and (b) they are fundamentally unsuccessful in
          communicating their results to designers.
        </p>
        <p>
          This work argues for a new kind of material intuition and prototypes a
          possible vector to aid its development.
        </p>
      </div>
    </template>
    <template #main>
      <AppBox width="medium" image="cycles/eagle-creek-fire-kristi-mccluer.jpg">
        <p>
          It's been almost ten years since I started studying and working in
          architecture. This was to be my last studio before beginning work on
          my master's thesis. Like for many of my peers, the looming climate
          crisis had been growing to take a bigger part of my daily life. I
          would spend Fridays on the streets protesting, but when I went back
          into the office on Monday, I was back to drawing plans for buildings
          that would propel the climate crisis even further. Yet, when I would
          try to talk my bosses and colleagues out of yet another concrete box,
          I would find myself fumbling.
        </p>
        <p>
          I had hunches and notions. But they didn't add up. Were there such
          things as <em>carbon-negative</em> materials? Did they even matter?
          How did the impact of construction compare to the use of a building?
          What did the word <em>sustainable</em> even mean for architecture? I
          could not finish my education like this.
        </p>
        <p>
          So I tried to find some answers. I joined
          <a href="https://www.architects4future.de">Architects for Future</a>,
          found peers to start
          <a href="https://faqconcrete.tumblr.com">FAQ concrete</a>, an interest
          group at the UdK architecture department, and tried my hand at a
          systematic read-up.
        </p>
        Photo by
        <a
          href="https://www.reddit.com/r/WTF/comments/6yajls/oregon_fires_next_to_a_golf_course/"
          >Kristi McCluer
        </a>
      </AppBox>
      <AppBox anchor="scope" width="small" image="scope.svg">
        <p>
          Let's start with some words on scope. The mess we find ourselves in
          touches more than just the emission of greenhouse gases. The
          transition to a sustainable practice of building requires a massive
          shift in many areas at once.
          <a href="http://www.bruno-latour.fr/node/754.html">Equity</a>,
          <a
            href="https://www.making-futures.com/jon-goodbun-on-the-possibility-of-an-ecological-dialogue/"
          >
            justice</a
          >,
          <a
            href="https://www.gsd.harvard.edu/2020/02/first-ever-compendium-of-indigenous-technologies-provides-a-powerful-toolkit-for-climate-resilient-design/"
            >resilience</a
          >,
          <a href="https://aabookshop.net/?wpsc-product=the-design-of-scarcity"
            >culture change</a
          >, etc., are interrelated sides to our same figurative sustainability
          coin.
        </p>
        <p>
          As architects, we tend to brush away the nitty-gritty in favour of big
          picture ideas. But dreaming up new futures<sup>1</sup> doesn't absolve
          us from dealing with the here and now. Every artefact, a desk, a
          chair, or the
          <a href="https://www.floatinguniversity.org/climate-care/"
            >Floating University Berlin</a
          >
          is embedded in and product of a system. Its physical existence in the
          world is manifested in tangible amounts of carbon that were put into
          the atmosphere when it's constituent elements were manufactured.<sup
            >2</sup
          >
          A fundamental opposition to these constituent realities, however
          uncomfortable, does not absolve us from our responsibility to navigate
          them. Especially when doing harm is easy and doing good is relatively
          difficult.
        </p>
        <ol class="footnotes">
          <li>
            <a href="https://en.wikipedia.org/wiki/Solarpunk"
              >A practice now more necessary than ever!</a
            >
          </li>
          <li>
            See
            <a href="#an-understanding-for-the-replenishment-of-ecosystems"
              >An Understanding for the Replenishment of Ecosystems</a
            >
          </li>
        </ol>
      </AppBox>
      <AppBox width="large" image="50-years-after-The-Limits-to-Growth.svg">
        <p>
          Before we can dive into the aforementioned nitty-gritty, we'll need to
          lay some more groundwork.
        </p>
        <p>
          So,
          <a
            href="https://gimletmedia.com/shows/howtosaveaplanet/v4h3x95/how-screwed-are-we"
            >how screwed are we?</a
          >
          These numbers are from a lecture at
          <a href="https://arch.ethz.ch">ETH's</a>
          <a href="https://block.arch.ethz.ch">Block Research Group</a>. I added
          the current
          <a href="https://climateactiontracker.org/global/cat-thermometer/"
            >global temperature projection</a
          >
          for context. The full text of <em>The Limits to Growth</em> is
          available
          <a href="https://www.clubofrome.org/publication/the-limits-to-growth/"
            >here</a
          >. As far as I know, the slides are not available online, but they
          provide the following sources:
        </p>
        <ul>
          <li>
            <a href="https://www.iea.org/reports/2018-global-status-report"
              >2018 Global Status Report
            </a>
          </li>
          <li>
            <a
              href="https://www.chathamhouse.org/2018/06/making-concrete-change-innovation-low-carbon-cement-and-concrete"
              >Chatham House
            </a>
          </li>
          <li>
            <a
              href="https://www.constructiondive.com/news/report-global-construction-waste-will-almost-double-by-2025/518874/"
              >Construction Dive
            </a>
          </li>
          <li>
            <a href="https://www.iea.org/reports/world-energy-outlook-2019"
              >World Energy Outlook 2019
            </a>
          </li>
        </ul>
      </AppBox>
      <AppBox width="medium" image="linear-extract.svg">
        <p>
          Let's back up a little more. For too long, humans have relied on a
          linear economic model, one that is fundamentally
          <a href="https://en.wikipedia.org/wiki/Extractivism">extractivist</a>.
          Raw materials are mined and refined only to be put in landfills at the
          end of a product's life. All this using the energy from burning fossil
          fuels, releasing carbon that had been stored in the ground for
          hundreds of millions of years into the atmosphere. This is
          fundamentally incompatible with a
          <a href="https://en.wikipedia.org/wiki/Planetary_boundaries"
            >finite system such as our planet</a
          >.
        </p>
      </AppBox>
      <AppBox width="medium" image="circular-borrow.svg">
        <p>
          In contrast,
          <a
            href="https://en.wikipedia.org/wiki/Circular_economy#Moving_away_from_the_linear_model"
            >a circular framework takes insights from living systems</a
          >. It conceives the production, use, and decomposition of goods as
          cycles of nutrients, matter, and energy in a closed loop. The tighter
          the loop, the less energy needs to be expended. We can thus read the
          diagram as a cascade of priorities:
        </p>
        <ol>
          <li>
            <a href="https://zukunftfueralle.jetzt/buch-zum-kongress/11-wohnen/"
              >Do we need it at all?</a
            >
            (In German)
          </li>
          <li><a href="https://rotordc.com">What is already there?</a></li>
          <li>
            <a href="https://gxn.3xn.com/project/building-circular-future"
              >Can we make something new out of something old?</a
            >
            And only then:
          </li>
          <li>
            How can we borrow something so that it can be looped back again?
          </li>
        </ol>
        <p>
          We're all well familiar with the three R's. But what if none of them
          apply? In the following, we'll focus on the instances when producing
          something new is indispensable.
        </p>
      </AppBox>
      <AppBox
        anchor="life-cycle-stages"
        width="large"
        image="life-cycle-stages.svg"
      >
        <p>
          Life-cycle assessments are a methodology to assess and quantify the
          environmental impact of products, processes, and services. The
          life-cycle of an artefact is divided into discrete
          <em>stages</em> that can be modelled with <em>inputs</em> and
          <em>outputs</em> of different dimensions within a
          <em>system boundary</em>. The diagram above shows these stages in
          relation to architecture.
        </p>
        <p>
          <a
            href="https://en.wikipedia.org/wiki/Life-cycle_assessment#Critiques"
            >It's important to note that this framework is to be understood as
            an attempt.</a
          >
          Due to the complex nature of production and sourcing, with their
          multitude of variables, they can never produce definitive results.
          They can not, for instance, capture aspects that not or not easily
          quantifiable, as many social aspects are. But they do provide a
          valuable comparative heuristic, as long as the individual subjects are
          sufficiently consistently modelled.
        </p>
      </AppBox>
      <AppBox
        anchor="flows"
        width="medium"
        image="cycles/process-laminated-veneer-board.jpg"
      >
        <p>
          Life-cycle information on products is compiled into so-called
          <a
            href="https://en.wikipedia.org/wiki/Environmental_product_declaration"
            >Environmental Product Declarations</a
          >
          or <em>EPDs</em>. The individual stages of a life-cycle are modelled
          in <em>flows</em>. Shown above is the flow of the
          <a
            href="http://www.oekobaudat.de/OEKOBAU.DAT/resource/datastocks/d92712a1-d516-462b-b37d-7497031e6e72/processes/b50f7b36-d9aa-40c5-b839-4925a1500952?format=html&lang=en"
            >production of laminated veneer board</a
          >.
        </p>
        <p>
          The
          <em
            >German Federal Ministry of the Interior, Building and Community</em
          >
          maintains a fairly comprehensive database of building materials and
          products, called
          <a href="https://www.oekobaudat.de/en.html">Ökobaudat</a>.
        </p>
      </AppBox>
      <AppBox width="medium" video="EPD-1080.mp4" autoplay loop>
        <p>
          <em>Ökobaudat's</em> <em>EPDs</em> necessarily cover a wide range of
          inputs and outputs. Unfortunately, this thoroughness also renders them
          virtually useless for architects and designers. Indicators such as
          <a
            href="https://www.oekobaudat.de/OEKOBAU.DAT/resource/lciamethods/b4274add-93b7-4905-a5e4-2e878c4e4216.xml"
          >
            Acidification potential</a
          >,
          <a
            href="https://www.oekobaudat.de/OEKOBAU.DAT/resource/lciamethods/f58827d0-b407-4ec6-be75-8b69efb98a0f.xml"
            >Eutrophication potential</a
          >, or
          <a
            href="https://www.oekobaudat.de/OEKOBAU.DAT/resource/lciamethods/f7c73bb9-ab1a-4249-9c6d-379a0de6f67e.xml"
            >Abiotic depletion potential for non-fossil resources</a
          >
          hardly provide actionable information.
        </p>
        <p>
          The
          <a
            href="https://www.oekobaudat.de/OEKOBAU.DAT/resource/lciamethods/77e416eb-a363-4258-a04e-171d843a6460.xml"
            >Global Warming Potential</a
          >
          or <em>GWP</em> of a product or process is quantified as a multiple of
          the heat that would be absorbed by the same mass of carbon dioxide. So
          <span class="nowrap">1 kg</span> of Carbon Dioxide has a
          <em>GWP</em> of 1, while <span class="nowrap">1 kg</span> of Methane
          has a <em>GWP</em> of 56 – 92. (<a
            href="https://en.wikipedia.org/wiki/Global_warming_potential#values"
            >Over 20 years</a
          >).
        </p>
        <p>
          The other big issue with these quantification methodologies is that
          they are introduced too late in the design process. To produce
          reasonably accurate results, instruments such as
          <em>life-cycle assessments</em> rely on detailed modelling of the
          proposed artefact. Most design decisions are locked in at that point.
          The decisions are made much earlier in the process – and often times
          unconsciously.
        </p>
      </AppBox>
      <AppBox
        width="large"
        image="an-understanding-for-the-replenishment-of-ecosystems.svg"
        anchor="an-understanding-for-the-replenishment-of-ecosystems"
      >
        <p>
          A circular mode of production implies that we don't consume more than
          what our habitats provide us with. We must therefore also introduce
          the concept of time. Human cultures have long reflected the
          temporalities of the cycles they were embedded in. Examples of this in
          Europe are
          <em>harvest festivals</em> or the celebration of <em>Midsummer</em>.
        </p>
        <ol class="footnotes">
          <li>
            Strictly speaking, even the notion of replenishment is a problematic
            one. It is a mindset of <em>extraction</em> and <em>scarcity</em>
            <span class="nowrap"
              >(see
              <a href="https://en.wikipedia.org/wiki/Planetary_boundaries">
                Planetary Boundaries</a
              >).</span
            >
          </li>
          <li>
            As in: regain awareness of our embeddedness. We were always part.
          </li>
        </ol>
      </AppBox>
      <AppBox width="medium" image="seasons-life-cycles.svg">
        <p>
          From the moment we pick up a pencil, we make decisions. We draw on
          implicit knowledge, <em>intuition</em>. Early decisions, such as the
          organisation of a storey, have implications for the supporting
          structure and thus for the materials that can be used. This is where
          we have to start.
        </p>
      </AppBox>
      <AppBox width="medium" image="land-use-as-metric.svg"
        ><p>
          Architecture is inseparably linked with space. To think
          architectonically means to think spatially.
        </p>
        <p>
          With time as the missing piece, we can map what we learned about
          <em>life-cycle assessments</em> back to the land and construct space
          as a metric to leverage our spatial intuition.
        </p>
      </AppBox>
      <AppBox width="medium" image="cycles/brandenburgs-forests.png">
        <p>
          Such a metric is tied to the metabolism of a specific landscape. It is
          inherently local and specific. Our framework, therefore, requires that
          we establish a
          <a href="#life-cycle-stages">system boundary</a>.
        </p>
        <p>
          We can think of Berlin and Brandenburg as such a system. Brandenburg's
          forests cover more than
          <span class="nowrap">12.000 km<sup>2</sup>,</span> approximately 40%
          of its area.
        </p>
      </AppBox>
      <AppBox width="large" image="mitigation-window.svg"
        ><p>
          We can now relate the emissions caused by the production of an
          architectural element to the area of forest in Brandenburg that would
          sequester those emissions in a given timeframe. We choose one year.
        </p>
        <p>
          (And, since this is hard science we're doing here, the area is also
          given in football fields!)
        </p>
      </AppBox>
      <AppBox width="medium" image="elements.svg">
        Let's do some modelling…
        <ul>
          <li>Columns</li>
          <li>Beams</li>
          <li>Walls</li>
          <li>Windows</li>
          <li>Doors</li>
          <li>Slabs</li>
          <li>Foundations</li>
        </ul>
      </AppBox>
      <AppBox width="medium" image="cycles/screenshot-numbers.png">
        <p>…and crunch some numbers.</p>
      </AppBox>
      <AppBox width="medium" image="cycles/screenshot-oekobaudat-csv.png">
        Spreadsheets grow big fast. Luckily, the
        <a href="https://www.oekobaudat.de/en.html">Ökobaudat</a> is made
        available to download.
      </AppBox>
      <AppBox width="medium" image="cycles/bbLCA-IDE.png"
        >Let's bust out our trusty
        <a href="https://www.grasshopper3d.com">Grasshopper</a> and do some
        parsing.
      </AppBox>
      <AppBox width="large" video="bbLCA-1080.mp4" autoplay loop>
        The result is an exploratory tool to intuitively assess and compare the
        environmental profile of architectural elements. I argue that in
        interacting with this tool, designers can develop new
        <em>intuitions</em>, implicit knowledge that is subconsciously recalled
        next time they pick up a pencil.
      </AppBox>
      <AppBox width="large" image="cycles/bbLCA-element.png">
        <p>
          The tool works by tallying the amount of each material that makes up a
          given element and retrieving the material's <em>GWP</em> from the
          database. The glulam wall shown above is composed of:
        </p>
        <ul>
          <li>
            <a
              href="https://oekobaudat.de/OEKOBAU.DAT/datasetdetail/process.xhtml?lang=en&uuid=703eec32-59af-47e1-9c91-4a32afe3187f&version=20.20.120"
              >Solid construction timber</a
            >
          </li>
          <li>
            <a
              href="https://oekobaudat.de/OEKOBAU.DAT/datasetdetail/process.xhtml?lang=en&uuid=393f494d-8738-4330-aa5e-1652bb29b574&version=20.19.120"
              >Wood fibre board</a
            >
          </li>
          <li>
            <a
              href="https://oekobaudat.de/OEKOBAU.DAT/datasetdetail/process.xhtml?uuid=e0a9e1c6-4dec-41b0-b9c1-c9e05010bc68&version=00.01.000&stock=OBD_2021_I&lang=de"
            >
              Cross-laminated timber</a
            >
          </li>
        </ul>
      </AppBox>

      <AppBox width="large" image="production-window.svg"
        ><p>
          So far, we have only looked at the status quo. To consider, for
          example, the electric energy expended in the production of a material,
          the corresponding
          <em>EPD</em> will use the country's electricity grid mix as an input.
          In Germany's case,
          <a
            href="https://www.umweltbundesamt.de/sites/default/files/medien/1410/publikationen/2019-04-10_cc_10-2019_strommix_2019.pdf"
            >its electricity mix is still predominantly non-renewable</a
          >.
        </p>
        <p>
          This is bound to change, albeit slowly. Can we modify our tool to
          depict a hypothetical future where all energy is generated from
          renewable sources?
        </p>
        <p>
          Now,
          <a
            href="https://www.economist.com/letters-to-the-editor-the-inbox/2007/07/15/the-perils-of-prediction-june-2nd"
            >it's tough to make predictions, especially about the future</a
          >. But we can use a <a href="#flows">flow's</a>
          <a href="https://en.wikipedia.org/wiki/Primary_energy"
            >primary energy input</a
          >
          for an approximation. If we relate the expended
          <em>primary energy</em> to the potential
          <a
            href="https://www.unendlich-viel-energie.de/media/file/319.Potenzialatlas_2_Auflage_Online.pdf"
            >energy productivity</a
          >
          of Brandenburg's landscapes, we can once again compare our
          architectural elements. This scenario does not consider biomass a
          renewable energy source, as its combustion would release the absorbed
          carbon back into the atmosphere and thus cancel out its sequestration
          effect. Brandenburg's potential energy productivity is there derived
          from how dense we can pack wind turbines.
        </p>
        <p>
          Most industrial processes require high temperatures. We must thus
          account for conversion losses from electricity to heat.
          <a
            href="https://www.er.tu-berlin.de/fileadmin/a38331300/Dateien/Technischer_Stand_und_Flexibilität_des_Power-to-Gas-Verfahrens.pdf"
            >Common methods use electrolysis to generate hydrogen, which can
            then be burnt</a
          >. Unfortunately, <em>Ökobaudat's</em> <em>EPDs</em> do not break down
          the ratio between electricity and heat, and these numbers are very
          hard to determine. So I had to fall back on a mix of dodgy sources and
          educated guesses.
        </p>
        <p>
          Still, with fossil fuels out of the picture, we can see that processes
          that use less thermal energy are at an even bigger advantage over
          those that require high temperatures, such as the production of
          cement. The gap between a rammed earth wall and one made out of
          concrete grows even bigger.
        </p>
      </AppBox>
      <AppBox width="medium" image="cycles/screenshot-bbLCA-glulam-wall.png">
        <p>
          This work hypothesises a vector to aid the development of a new kind
          of material intuition. It is, however, important to consider the
          limitations of this approach.
        </p>
        <ol>
          <li>
            This tool is a <em>Proof-of-Concept</em> rather than a turn-key
            solution. It is prototyped on top of the popular
            <a href="https://www.rhino3d.com">Rhino 3D</a> CAD software. As
            such, its setup is rather involved and prone to bugs.
          </li>
          <li>
            Due to limitations of the underlying <em>Ökobaudat</em>, only the
            <em>Cradle to Gate</em> stages of elements are considered.
          </li>
          <li>
            <em>EPDs</em> have the status quo <em>baked in</em>. Hypotheses
            about renewable energy scenarios can only be made with the inclusion
            of additional data that is not readily available.
          </li>
        </ol>
        <p></p>
      </AppBox>

      <AppBox width="large" image="cycles/cycles-relations.png"
        ><em>Appendix</em>
        <p>
          <em>LCAs</em> are a valuable tool. Architects fancy themselves
          engineers, but something is lost when we communicate through numbers
          alone. Besides, I argue that this should not remain an experts'
          discourse. This concerns all of us. We need a cultural shift in what
          we think of as buildings.
          <a href="#scope">We collectively need to imagine new futures</a>.
        </p>
        <p>
          The construction industry is not going to change without societies
          creating fair and equitable rules. The figurative level playing field,
          but a global one.
        </p>
        <p>
          Only an informed public can elect to implement effective and just
          policies. It is our job as experts to understand and communicate the
          challenges in our field and create an awareness and understanding of
          what's at stake. Tools such as the one presented in this work can aid
          that. The strategy of inducing implicit knowledges is therefore not
          limited to architects and planners. To influence the notion of a house
          and instil desire for a new kind of architecture means to also create
          the conditions for such an architecture to emerge. Public labs could
          serve as discursive spaces to imagine and prototype. Acting as nodes
          in a web of relations, they could play an important part in tackling
          the enormous issue that lies ahead.
        </p>
      </AppBox>
    </template>
  </AppProject>
</template>

<script>
export default {}
</script>

<style lang="sass" scoped></style>

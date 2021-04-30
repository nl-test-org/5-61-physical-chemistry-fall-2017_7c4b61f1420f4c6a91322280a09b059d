---
about_this_resource_text: '<p><strong>Description</strong>: This lecture covers classical
  wave equations, the separation of variables, boundary conditions, and the superposition
  of normal modes: &quot;the pluck.&quot;</p><p><strong>Instructor</strong>: Prof.
  Robert Field&nbsp;</p>'
course_id: 5-61-physical-chemistry-fall-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: SSVdDcC2LrQ
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  title: Video-YouTube-Stream
  type: Video
  uid: 254872b3e326c494fc2355c74d7589fd
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT5.61F17/MIT5_61F17_Lecture_04_300k.mp4
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  title: Video-Internet Archive-MP4
  type: Video
  uid: 902391817e567dacb68f38a42b98fa35
- id: 3Play-3PlayYouTubeid-MP4
  media_location: SSVdDcC2LrQ
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a7d59745b0f033b95306fef13c150412
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/SSVdDcC2LrQ/default.jpg
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 01fb4ea0c82ec5362280e97ac4e78674
- id: SSVdDcC2LrQ.srt
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  technical_location: https://ocw.mit.edu/courses/chemistry/5-61-physical-chemistry-fall-2017/lecture-videos/classical-wave-equation-and-separation-of-variables/SSVdDcC2LrQ.srt
  title: 3play caption file
  type: null
  uid: 7ff6e21aa3676d2cf3d190e7b8747239
- id: SSVdDcC2LrQ.pdf
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  technical_location: https://ocw.mit.edu/courses/chemistry/5-61-physical-chemistry-fall-2017/lecture-videos/classical-wave-equation-and-separation-of-variables/SSVdDcC2LrQ.pdf
  title: 3play pdf file
  type: null
  uid: ede1f6543bfb51f16a57901abb00349b
- id: Caption-3Play YouTube id-SRT_1
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 19868e84d2e07d9e7729e055df63434f
- id: Transcript-3Play YouTube id-PDF_1
  parent_uid: 305ef304673ee0782f6ea89ad959e4fd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 89802d4be9bea41eb8b99dd7de67e671
inline_embed_id: 99369904classicalwaveequationandseparationofvariables80400218
layout: video
order_index: null
parent_uid: bcdc517fdf2bc2d6276bad5ba6f0953b
related_resources_text: ''
short_url: classical-wave-equation-and-separation-of-variables
technical_location: https://ocw.mit.edu/courses/chemistry/5-61-physical-chemistry-fall-2017/lecture-videos/classical-wave-equation-and-separation-of-variables
template_type: Tabbed
title: 'Lecture 4: Classical Wave Equation and Separation of Variables'
transcript: <p><span m="115">The</span> <span m="160">following</span> <span m="610">content</span>
  <span m="1120">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1960">Creative</span> <span m="2410">Commons</span>
  <span m="2800">license.</span> <span m="3830">Your</span> <span m="3910">support</span>
  <span m="4390">will</span> <span m="4570">help</span> <span m="4840">MIT</span>
  <span m="5290">Open</span> <span m="5530">Courseware</span> <span m="6040">continue</span>
  <span m="6520">to</span> <span m="6670">offer</span> <span m="7000">high</span>
  <span m="7210">quality</span> <span m="7690">educational</span> <span m="8350">resources</span>
  <span m="8920">for</span> <span m="9070">free.</span> <span m="10130">To</span>
  <span m="10230">make</span> <span m="10330">a</span> <span m="10390">donation</span>
  <span m="11170">or</span> <span m="11320">to</span> <span m="11440">view</span>
  <span m="11650">additional</span> <span m="12070">materials</span> <span m="12670">from</span>
  <span m="12850">hundreds</span> <span m="13180">of</span> <span m="13300">MIT</span>
  <span m="13660">courses,</span> <span m="14960">visit</span> <span m="15160">MIT</span>
  <span m="15670">Open</span> <span m="15940">Courseware</span> <span m="16630">at</span>
  <span m="16780">ocw.mit.edu.</span></p><p><span m="22640">ROBERT FIELD:</span> <span
  m="22775">That's</span> <span m="22910">the</span> <span m="23060">outline</span>
  <span m="23480">of</span> <span m="23570">what</span> <span m="23690">we're</span>
  <span m="23810">going</span> <span m="23980">to</span> <span m="24080">cover.</span>
  <span m="24740">But</span> <span m="24950">before</span> <span m="25280">we</span>
  <span m="25400">get</span> <span m="25550">started</span> <span m="26000">on</span>
  <span m="26150">that,</span> <span m="26880">I</span> <span m="26980">want</span>
  <span m="27020">to</span> <span m="27080">talk</span> <span m="27380">about</span>
  <span m="27620">a</span> <span m="27680">couple</span> <span m="28040">of</span>
  <span m="28430">things.</span> <span m="29910">First</span> <span m="30170">of</span>
  <span m="30290">all,</span> <span m="31650">last</span> <span m="31920">time,</span>
  <span m="32159">we</span> <span m="32280">talked</span> <span m="32580">about</span>
  <span m="33210">the two</span> <span m="33450">slit</span> <span m="33750">experiment.</span>
  <span m="36080">And</span> <span m="36270">it's</span> <span m="36480">mostly</span>
  <span m="37140">classical.</span> <span m="37870">There</span> <span m="37980">is</span>
  <span m="38160">only</span> <span m="38610">a</span> <span m="38670">little</span>
  <span m="38940">bit</span> <span m="39120">of</span> <span m="39180">quantum</span>
  <span m="39780">in</span> <span m="39960">it</span> <span m="40220">where</span>
  <span m="40430">we</span> <span m="41880">talk</span> <span m="42240">about</span>
  <span m="43530">momentum</span> <span m="45380">as</span> <span m="45540">being</span>
  <span m="45840">determined</span> <span m="46350">by</span> <span m="46740">h</span>
  <span m="47100">over</span> <span m="47300">lambda.</span> <span m="48390">OK.</span>
  <span m="48660">But</span> <span m="50700">what</span> <span m="50880">were</span>
  <span m="51000">the</span> <span m="51120">two</span> <span m="51450">surprising</span>
  <span m="52230">things</span> <span m="53400">about</span> <span m="53700">the</span>
  <span m="53820">two</span> <span m="54060">slit</span> <span m="54360">experiment?</span>
  <span m="54930">There</span> <span m="55130">are</span> <span m="55230">two</span>
  <span m="55540">of</span> <span m="55660">them,</span> <span m="57010">two</span>
  <span m="57190">surprises.</span> <span m="58000">Yes?</span></p><p><span m="58360">AUDIENCE:</span>
  <span m="58450">[INAUDIBLE]</span> <span m="60760">That</span> <span m="60870">a</span>
  <span m="61240">single</span> <span m="61380">particle</span> <span m="61600">can</span>
  <span m="61920">interfere</span> <span m="62170">with</span> <span m="62545">itself.</span></p><p><span
  m="62920">ROBERT FIELD:</span> <span m="63115">Yes.</span> <span m="63310">That's</span>
  <span m="65470">the</span> <span m="65620">most</span> <span m="65950">surprising</span>
  <span m="66580">thing.</span> <span m="67360">And</span> <span m="70240">when</span>
  <span m="70480">you</span> <span m="70600">go</span> <span m="70960">to</span> <span
  m="71410">really</span> <span m="71860">low</span> <span m="72040">intensity--</span>
  <span m="73310">so</span> <span m="73420">there's</span> <span m="73630">only</span>
  <span m="73900">one</span> <span m="74200">photon,</span> <span m="74980">which</span>
  <span m="75220">is</span> <span m="75400">quantum,</span> <span m="77200">in</span>
  <span m="77410">the</span> <span m="77560">apparatus,</span> <span m="78880">somehow,</span>
  <span m="79540">it</span> <span m="79750">knows</span> <span m="80470">enough</span>
  <span m="80920">to</span> <span m="81100">interfere</span> <span m="81490">with</span>
  <span m="81700">itself.</span> <span m="83220">And</span> <span m="83820">this</span>
  <span m="84090">is</span> <span m="84740">the</span> <span m="85590">most</span>
  <span m="86940">mysterious</span> <span m="87870">aspect.</span> <span m="89110">But</span>
  <span m="89160">then</span> <span m="90450">there's</span> <span m="90660">one</span>
  <span m="90900">other</span> <span m="91140">aspect,</span> <span m="92550">which</span>
  <span m="93030">is</span> <span m="93780">how</span> <span m="94230">it</span> <span
  m="95310">communicates</span> <span m="96060">that</span> <span m="96270">interference</span>
  <span m="96810">with</span> <span m="96990">itself.</span> <span m="99850">What</span>
  <span m="99980">is</span> <span m="100130">that?</span> <span m="106590">You're</span>
  <span m="106700">hot.</span> <span m="107010">You</span> <span m="107070">want</span>
  <span m="107220">to</span> <span m="107320">do</span> <span m="107480">another</span>
  <span m="107890">one?</span></p><p><span m="108375">AUDIENCE:</span> <span m="108547">What</span>
  <span m="108720">do</span> <span m="108890">you</span> <span m="109010">mean</span>
  <span m="109190">by</span> <span m="109662">how</span> <span m="110134">it</span>
  <span m="110606">communicates?</span></p><p><span m="111080">ROBERT FIELD:</span>
  <span m="111230">Well,</span> <span m="111380">here</span> <span m="111590">we</span>
  <span m="111740">have</span> <span m="112470">the</span> <span m="114270">screen</span>
  <span m="114950">on</span> <span m="115100">which</span> <span m="116600">the</span>
  <span m="116870">information</span> <span m="117590">is</span> <span m="117770">deposited.</span>
  <span m="120070">And</span> <span m="121600">you</span> <span m="121780">have</span>
  <span m="123190">possibly</span> <span m="123980">some</span> <span m="124510">sort</span>
  <span m="124780">of</span> <span m="125590">probability</span> <span m="126370">distribution,</span>
  <span m="127580">which</span> <span m="127690">is</span> <span m="127820">a</span>
  <span m="127900">kind</span> <span m="128139">of</span> <span m="128259">a</span>
  <span m="128320">continuous</span> <span m="129039">thing.</span> <span m="129820">But</span>
  <span m="130000">you</span> <span m="130120">don't</span> <span m="130330">observe</span>
  <span m="130690">that.</span> <span m="134780">What do</span> <span m="135110">you</span>
  <span m="135290">observe?</span> <span m="136740">So</span> <span m="137180">you</span>
  <span m="137300">could</span> <span m="137510">say</span> <span m="137870">the</span>
  <span m="138020">state</span> <span m="138620">of</span> <span m="140120">a</span>
  <span m="140210">particle</span> <span m="141320">has</span> <span m="142400">amplitude</span>
  <span m="143090">everywhere</span> <span m="144890">on</span> <span m="145100">this</span>
  <span m="145490">screen.</span> <span m="146430">But</span> <span m="147800">what</span>
  <span m="148100">do</span> <span m="148130">you</span> <span m="148340">see</span>
  <span m="148790">in</span> <span m="148910">the</span> <span m="149060">experiment?</span>
  <span m="152010">Yes?</span></p><p><span m="153410">AUDIENCE:</span> <span m="153485">So
  you</span> <span m="153560">just</span> <span m="153740">see</span> <span m="154320">one</span>
  <span m="155220">[INAUDIBLE]</span> <span m="155840">point.</span> <span m="156290">[INAUDIBLE]</span>
  <span m="157190">thousands</span> <span m="157670">and</span> <span m="157760">thousands.</span>
  <span m="158310">And</span> <span m="158450">eventually,</span> <span m="158900">you
  see</span> <span m="159520">it mimic</span> <span m="159800">that</span> <span m="160260">probability</span>
  <span m="160660">[? sequence. ?]</span></p><p><span m="161270">ROBERT FIELD:</span>
  <span m="161465">That's</span> <span m="161660">exactly</span> <span m="162200">right.</span>
  <span m="163530">So</span> <span m="164240">this</span> <span m="164540">state</span>
  <span m="164900">of</span> <span m="164990">the</span> <span m="165080">system</span>
  <span m="165530">which</span> <span m="165770">is</span> <span m="165920">distributed</span>
  <span m="167660">collapses</span> <span m="169070">to</span> <span m="169280">a</span>
  <span m="169340">single</span> <span m="169700">point.</span> <span m="171490">We</span>
  <span m="171670">say</span> <span m="172210">that</span> <span m="172840">what</span>
  <span m="173020">we</span> <span m="173770">are</span> <span m="173920">observing--</span>
  <span m="175310">and</span> <span m="175480">this</span> <span m="175660">is</span>
  <span m="175780">mysterious.</span> <span m="176500">And</span> <span m="176890">it</span>
  <span m="176980">should</span> <span m="177430">bother</span> <span m="177790">you</span>
  <span m="178060">now.</span> <span m="179800">We're</span> <span m="180010">seeing</span>
  <span m="180580">an</span> <span m="181120">eigenvalue</span> <span m="182560">of</span>
  <span m="182710">the</span> <span m="182830">measurement</span> <span m="183370">operator.</span>
  <span m="185950">So</span> <span m="186280">we</span> <span m="186490">have</span>
  <span m="186850">this</span> <span m="187030">sort</span> <span m="187240">of</span>
  <span m="187300">thing.</span> <span m="188080">It</span> <span m="188200">goes</span>
  <span m="188500">into</span> <span m="188710">the</span> <span m="188830">measurement</span>
  <span m="189250">operator.</span> <span m="190060">And</span> <span m="190190">the</span>
  <span m="190460">measurement</span> <span m="190810">operator</span> <span m="191320">says,</span>
  <span m="192010">this</span> <span m="192280">is</span> <span m="192880">one</span>
  <span m="193090">of</span> <span m="193210">the</span> <span m="193360">answers</span>
  <span m="193810">I'm</span> <span m="193960">permitted</span> <span m="194410">to</span>
  <span m="194500">give</span> <span m="194740">you.</span></p><p><span m="196930">And</span>
  <span m="197410">another</span> <span m="198010">aspect</span> <span m="198590">that's</span>
  <span m="198760">really</span> <span m="199690">disturbing</span> <span m="200620">or</span>
  <span m="200800">puzzling</span> <span m="201970">is</span> <span m="202330">that</span>
  <span m="202540">you</span> <span m="202720">do</span> <span m="204370">many</span>
  <span m="204940">identical</span> <span m="205600">experiments.</span> <span m="207160">And</span>
  <span m="207280">the</span> <span m="207400">answer</span> <span m="207700">is</span>
  <span m="207820">always</span> <span m="208120">different.</span> <span m="213820">There</span>
  <span m="214010">is</span> <span m="214110">no</span> <span m="214290">determinant.</span>
  <span m="216090">It's</span> <span m="216330">all</span> <span m="216540">probabilistic.</span>
  <span m="217920">So</span> <span m="218100">this</span> <span m="218520">really</span>
  <span m="220320">should</span> <span m="220560">bother</span> <span m="220950">you.</span>
  <span m="221610">And</span> <span m="222030">eventually,</span> <span m="222660">it</span>
  <span m="222750">won't.</span></p><p><span m="224710">OK.</span> <span m="226970">Now,</span>
  <span m="227180">there's</span> <span m="227420">another</span> <span m="227930">question</span>
  <span m="228380">I</span> <span m="228500">have.</span> <span m="229430">When</span>
  <span m="229610">I</span> <span m="229700">described</span> <span m="231630">the</span>
  <span m="231800">two</span> <span m="232010">slit</span> <span m="232340">experiment,</span>
  <span m="234040">I</span> <span m="234160">intentionally</span> <span m="234940">put</span>
  <span m="235150">something</span> <span m="235540">up</span> <span m="235720">on</span>
  <span m="235840">the</span> <span m="235960">diagram</span> <span m="237770">that</span>
  <span m="237920">should</span> <span m="238100">bother</span> <span m="238500">you,</span>
  <span m="238880">that</span> <span m="239270">should</span> <span m="239690">have</span>
  <span m="239870">said,</span> <span m="240170">this</span> <span m="240380">is</span>
  <span m="240500">ridiculous.</span> <span m="242420">I</span> <span m="242480">used</span>
  <span m="242690">a</span> <span m="242780">candle</span> <span m="244000">in</span>
  <span m="244100">the</span> <span m="244190">lecture.</span> <span m="244760">And</span>
  <span m="244910">I</span> <span m="244970">used</span> <span m="245180">a</span>
  <span m="245270">light</span> <span m="245600">bulb</span> <span m="246530">in</span>
  <span m="246620">the</span> <span m="246710">notes.</span> <span m="248990">And</span>
  <span m="249110">why</span> <span m="249320">is</span> <span m="249470">that</span>
  <span m="249620">ridiculous?</span> <span m="251490">Yes?</span></p><p><span m="252240">AUDIENCE:</span>
  <span m="252285">You</span> <span m="252330">said</span> <span m="252550">many</span>
  <span m="252710">frequencies.</span></p><p><span m="254250">ROBERT FIELD:</span>
  <span m="254370">That's</span> <span m="254490">right.</span> <span m="254850">So</span>
  <span m="257640">the</span> <span m="257760">sources</span> <span m="258329">of</span>
  <span m="258510">light</span> <span m="258890">that</span> <span m="259290">I</span>
  <span m="260370">misled</span> <span m="261000">you</span> <span m="261390">with</span>
  <span m="261720">intentionally</span> <span m="262890">have</span> <span m="263100">a</span>
  <span m="263160">continuous</span> <span m="264120">frequency</span> <span m="264690">distribution.</span>
  <span m="266890">And</span> <span m="267580">the</span> <span m="269110">interference</span>
  <span m="270250">depends</span> <span m="271030">on</span> <span m="272680">the</span>
  <span m="272800">same</span> <span m="273190">frequency.</span> <span m="274640">So</span>
  <span m="276370">the</span> <span m="276520">only</span> <span m="276910">way</span>
  <span m="277210">you</span> <span m="277380">would</span> <span m="277480">see</span>
  <span m="277750">any</span> <span m="278080">kind</span> <span m="278650">of</span>
  <span m="280570">diffraction</span> <span m="281260">pattern,</span> <span m="281740">any</span>
  <span m="281980">kind</span> <span m="282310">of</span> <span m="282520">pattern</span>
  <span m="282970">on</span> <span m="283090">the</span> <span m="283150">two</span>
  <span m="283330">slit</span> <span m="283570">experiment,</span> <span m="284440">is</span>
  <span m="284590">if</span> <span m="284710">you</span> <span m="284860">had</span>
  <span m="285280">monochromatic</span> <span m="286120">light.</span> <span m="288180">It</span>
  <span m="288270">would</span> <span m="288450">all</span> <span m="288690">wash</span>
  <span m="289050">out.</span> <span m="290220">You'd</span> <span m="290370">still</span>
  <span m="290640">get</span> <span m="290850">dots.</span> <span m="292170">But</span>
  <span m="292290">the</span> <span m="292380">dots</span> <span m="292710">would</span>
  <span m="292860">never</span> <span m="293250">give</span> <span m="293490">you</span>
  <span m="293640">anything</span> <span m="294120">except</span> <span m="294450">perhaps</span>
  <span m="296360">a</span> <span m="296460">superposition</span> <span m="297240">of</span>
  <span m="297360">two</span> <span m="297750">or</span> <span m="297870">three</span>
  <span m="298290">or</span> <span m="298410">an</span> <span m="298530">infinite</span>
  <span m="298890">number</span> <span m="299880">of</span> <span m="300180">patterns.</span>
  <span m="302570">OK.</span> <span m="303020">This</span> <span m="303260">is,</span>
  <span m="303920">again,</span> <span m="304340">something</span> <span m="304730">that's</span>
  <span m="305750">really</span> <span m="306120">bothersome.</span></p><p><span m="308300">Now,</span>
  <span m="308600">I</span> <span m="308720">also</span> <span m="309170">use</span>
  <span m="309710">the</span> <span m="310820">crude</span> <span m="311720">illustration</span>
  <span m="312530">of</span> <span m="312980">an</span> <span m="313160">uncertainty</span>
  <span m="313610">principle,</span> <span m="314180">that</span> <span m="314780">the</span>
  <span m="314930">uncertainty</span> <span m="315530">in</span> <span m="315650">position</span>
  <span m="316980">z-axis</span> <span m="318320">and</span> <span m="318410">the</span>
  <span m="318530">uncertainty</span> <span m="319250">in</span> <span m="319430">the</span>
  <span m="319970">momentum</span> <span m="320420">along</span> <span m="320790">the</span>
  <span m="321050">z-axis</span> <span m="321950">was</span> <span m="322370">greater</span>
  <span m="322850">than</span> <span m="323210">h.</span> <span m="326720">And</span>
  <span m="328500">I</span> <span m="328760">froze.</span> <span m="329240">And</span>
  <span m="329330">I</span> <span m="329450">didn't</span> <span m="329750">realize</span>
  <span m="330470">that</span> <span m="330650">I</span> <span m="331700">had</span>
  <span m="331880">delta</span> <span m="332270">s</span> <span m="333320">with</span>
  <span m="333590">the</span> <span m="333720">slit.</span> <span m="334760">But</span>
  <span m="334940">it</span> <span m="335030">really</span> <span m="335390">is</span>
  <span m="335780">the</span> <span m="335900">same</span> <span m="336200">thing</span>
  <span m="336440">as</span> <span m="336650">the</span> <span m="337190">z.</span>
  <span m="337580">Because</span> <span m="338360">the</span> <span m="338450">slit</span>
  <span m="338930">is</span> <span m="339290">how</span> <span m="339530">you</span>
  <span m="339710">define</span> <span m="340670">the</span> <span m="340910">position</span>
  <span m="342110">in</span> <span m="342230">the</span> <span m="342380">z-axis.</span>
  <span m="343640">And</span> <span m="343790">so</span> <span m="344120">this</span>
  <span m="344360">is</span> <span m="344720">the</span> <span m="346100">first</span>
  <span m="346610">taste</span> <span m="347210">of</span> <span m="347360">the</span>
  <span m="347480">uncertainty</span> <span m="347900">principle.</span> <span m="348710">And</span>
  <span m="348860">I</span> <span m="348950">said</span> <span m="349190">I</span>
  <span m="349250">didn't</span> <span m="349520">like</span> <span m="349760">it.</span></p><p><span
  m="356050">OK.</span> <span m="357770">In</span> <span m="357910">quantum</span>
  <span m="358210">mechanics,</span> <span m="363120">you're</span> <span m="363290">not</span>
  <span m="363530">allowed</span> <span m="363890">to</span> <span m="364010">look</span>
  <span m="364220">inside</span> <span m="364640">small</span> <span m="364910">stuff.</span>
  <span m="365600">You're</span> <span m="365780">not</span> <span m="366020">allowed</span>
  <span m="366920">to</span> <span m="367070">see</span> <span m="367880">the</span>
  <span m="368030">microscopic</span> <span m="368840">structure.</span> <span m="369830">You're</span>
  <span m="370010">only</span> <span m="370400">able</span> <span m="370700">to</span>
  <span m="370850">do</span> <span m="371270">experiments,</span> <span m="372050">usually</span>
  <span m="373430">thought</span> <span m="373730">experiments,</span> <span m="375100">an</span>
  <span m="375190">infinite</span> <span m="375590">number</span> <span m="376070">of</span>
  <span m="376250">identical</span> <span m="376760">experiments.</span> <span m="377540">And</span>
  <span m="377660">they</span> <span m="378320">reveal</span> <span m="380060">the</span>
  <span m="380270">structure</span> <span m="381410">in</span> <span m="381560">some</span>
  <span m="382910">complicated,</span> <span m="384020">encoded</span> <span m="384560">way.</span></p><p><span
  m="385580">And</span> <span m="385700">this</span> <span m="385910">is</span> <span
  m="386060">really</span> <span m="386450">not</span> <span m="386870">what</span>
  <span m="387140">the</span> <span m="387230">textbooks</span> <span m="387800">are</span>
  <span m="387920">about.</span> <span m="389950">Textbooks</span> <span m="390460">don't</span>
  <span m="390790">tell</span> <span m="391090">you</span> <span m="393340">how</span>
  <span m="393550">you</span> <span m="393730">actually</span> <span m="394330">think</span>
  <span m="394690">about</span> <span m="394960">a</span> <span m="395020">problem</span>
  <span m="395420">with</span> <span m="395500">quantum</span> <span m="395770">mechanics.</span>
  <span m="396640">They</span> <span m="396820">tell</span> <span m="397060">you,</span>
  <span m="397630">here</span> <span m="397870">are</span> <span m="397990">some</span>
  <span m="398200">exactly</span> <span m="398680">solved</span> <span m="398950">problems.</span>
  <span m="399940">Memorize</span> <span m="400540">them.</span> <span m="402320">And</span>
  <span m="402440">I</span> <span m="402590">don't</span> <span m="402740">want</span>
  <span m="402910">you--</span> <span m="403130">I</span> <span m="403280">don't</span>
  <span m="403430">want</span> <span m="403580">to</span> <span m="403640">do</span>
  <span m="403820">that.</span></p><p><span m="407480">OK.</span> <span m="409870">Last</span>
  <span m="410260">part</span> <span m="410500">of</span> <span m="410590">the</span>
  <span m="410710">introduction</span> <span m="412060">here--</span> <span m="413240">suppose</span>
  <span m="413560">we</span> <span m="413710">have</span> <span m="413890">a</span>
  <span m="413950">circular</span> <span m="414520">drum,</span> <span m="416680">a</span>
  <span m="416800">square</span> <span m="417130">drum,</span> <span m="418810">and</span>
  <span m="419770">a</span> <span m="420250">rectangular</span> <span m="421000">drum.</span>
  <span m="425320">Have</span> <span m="425440">you</span> <span m="425530">ever</span>
  <span m="425710">seen</span> <span m="425950">a</span> <span m="425980">square</span>
  <span m="426310">drum</span> <span m="427981">or</span> <span m="428440">a</span>
  <span m="428560">rectangular</span> <span m="429220">drum?</span> <span m="431510">Do</span>
  <span m="431570">you</span> <span m="431660">have</span> <span m="431810">an</span>
  <span m="431900">idea</span> <span m="432320">how</span> <span m="432590">a</span>
  <span m="432650">square</span> <span m="433010">drum</span> <span m="433280">would</span>
  <span m="433400">sound?</span> <span m="436910">Yes.</span> <span m="437120">You</span>
  <span m="437270">do</span> <span m="437510">have</span> <span m="437720">an</span>
  <span m="437810">idea.</span> <span m="438410">It</span> <span m="438500">would</span>
  <span m="438680">sound</span> <span m="438890">terrible.</span> <span m="442460">Because</span>
  <span m="443030">the</span> <span m="443150">frequencies,</span> <span m="443910">you</span>
  <span m="443930">get</span> <span m="444740">are</span> <span m="444860">not</span>
  <span m="445070">integer</span> <span m="445430">multiples.</span> <span m="447450">It</span>
  <span m="447570">would</span> <span m="447660">just</span> <span m="448020">sound</span>
  <span m="448830">amazingly</span> <span m="449550">terrible.</span></p><p><span
  m="449970">But</span> <span m="451610">if</span> <span m="451790">you</span> <span
  m="451970">had</span> <span m="452270">a</span> <span m="452300">square</span> <span
  m="452630">drum</span> <span m="453862">or</span> <span m="454270">a</span> <span
  m="454390">rectangular</span> <span m="455080">drum,</span> <span m="455860">you</span>
  <span m="455980">could</span> <span m="456130">do</span> <span m="456310">an</span>
  <span m="456430">experiment</span> <span m="457210">with</span> <span m="457540">some</span>
  <span m="457780">kind</span> <span m="458080">of</span> <span m="458620">acoustic</span>
  <span m="459430">instrument</span> <span m="460100">to</span> <span m="460210">find</span>
  <span m="460540">out</span> <span m="460660">what</span> <span m="460930">the</span>
  <span m="461230">frequency</span> <span m="462340">distribution</span> <span m="463150">is</span>
  <span m="463740">of</span> <span m="464050">the</span> <span m="464200">noise</span>
  <span m="464590">you</span> <span m="464710">make.</span> <span m="465820">And</span>
  <span m="465970">you</span> <span m="466120">would</span> <span m="466270">be</span>
  <span m="466420">able</span> <span m="466540">to</span> <span m="466660">tell.</span>
  <span m="467470">It's</span> <span m="467650">not</span> <span m="467860">round.</span>
  <span m="469300">It</span> <span m="469870">might</span> <span m="470080">be</span>
  <span m="470230">square.</span> <span m="471310">Or</span> <span m="471460">it</span>
  <span m="471550">might</span> <span m="471760">have</span> <span m="471970">a</span>
  <span m="472030">certain</span> <span m="472300">ratio</span> <span m="473080">of</span>
  <span m="473770">dimensions.</span></p><p><span m="474220">This</span> <span m="474460">is</span>
  <span m="474550">what</span> <span m="474670">we're</span> <span m="474790">talking</span>
  <span m="475120">about</span> <span m="475840">as</span> <span m="475990">far</span>
  <span m="476290">as</span> <span m="476770">internal</span> <span m="477280">structure</span>
  <span m="477730">is</span> <span m="477880">concerned.</span> <span m="478960">And</span>
  <span m="479140">it's</span> <span m="479320">very</span> <span m="479620">much</span>
  <span m="479890">like</span> <span m="480250">what</span> <span m="480460">you</span>
  <span m="480580">would</span> <span m="480700">do</span> <span m="480940">as</span>
  <span m="481060">a</span> <span m="481120">musician.</span> <span m="484100">I</span>
  <span m="484160">mean,</span> <span m="484340">certainly,</span> <span m="484910">when</span>
  <span m="485750">a</span> <span m="485810">musical</span> <span m="486290">instrument</span>
  <span m="486890">is</span> <span m="487130">arranged</span> <span m="487550">correctly,</span>
  <span m="489230">it's</span> <span m="489410">not</span> <span m="489620">like</span>
  <span m="489860">a</span> <span m="489920">square</span> <span m="490250">drum.</span>
  <span m="491780">It</span> <span m="491930">sounds</span> <span m="492260">good.</span>
  <span m="493980">And</span> <span m="494100">that's</span> <span m="494340">because</span>
  <span m="495240">you</span> <span m="495420">get</span> <span m="495660">harmonics</span>
  <span m="496800">or</span> <span m="496920">you</span> <span m="497070">get</span>
  <span m="498240">integer</span> <span m="498630">multiples</span> <span m="499440">of</span>
  <span m="499680">some</span> <span m="501180">standard</span> <span m="501720">frequency.</span></p><p><span
  m="504880">OK.</span> <span m="505350">So</span> <span m="505620">now,</span> <span
  m="507560">we're</span> <span m="507740">going</span> <span m="507850">to</span>
  <span m="508010">talk</span> <span m="508430">about</span> <span m="510260">the</span>
  <span m="510470">classical</span> <span m="510980">wave</span> <span m="511250">equation,</span>
  <span m="512960">which</span> <span m="513039">is</span> <span m="513130">not</span>
  <span m="513340">quantum.</span> <span m="514960">But</span> <span m="515140">it's</span>
  <span m="516390">a</span> <span m="516460">very</span> <span m="516820">similar</span>
  <span m="517390">sort</span> <span m="517780">of</span> <span m="518230">equation</span>
  <span m="518830">to</span> <span m="519070">the</span> <span m="519309">Schrodinger</span>
  <span m="519880">equation.</span> <span m="521240">And</span> <span m="521289">so</span>
  <span m="521590">the</span> <span m="521710">methods</span> <span m="522130">for</span>
  <span m="522280">solving</span> <span m="522820">this</span> <span m="523000">differential</span>
  <span m="523570">equation</span> <span m="524740">are</span> <span m="526000">on</span>
  <span m="526210">display.</span> <span m="526960">And</span> <span m="527140">so</span>
  <span m="527980">the</span> <span m="528520">trick</span> <span m="529740">is--</span>
  <span m="530020">well,</span> <span m="530200">first</span> <span m="530530">of</span>
  <span m="530650">all,</span> <span m="532880">where</span> <span m="532960">does</span>
  <span m="533110">this</span> <span m="533290">equation</span> <span m="533740">come</span>
  <span m="533950">from?</span> <span m="535800">And</span> <span m="535920">it's</span>
  <span m="536190">always</span> <span m="536700">force</span> <span m="536955">is</span>
  <span m="537210">equal</span> <span m="537420">to</span> <span m="537510">mass</span>
  <span m="537780">times</span> <span m="538020">acceleration</span> <span m="538740">in</span>
  <span m="538930">disguise.</span></p><p><span m="540590">OK.</span> <span m="540980">And</span>
  <span m="541130">then</span> <span m="542270">you</span> <span m="542420">have</span>
  <span m="543440">tricks</span> <span m="543800">for</span> <span m="543920">how</span>
  <span m="544160">you</span> <span m="544310">solve</span> <span m="544670">this.</span>
  <span m="545700">And</span> <span m="545780">one</span> <span m="545990">of</span>
  <span m="546080">the</span> <span m="546230">most</span> <span m="546500">frequently</span>
  <span m="547850">used</span> <span m="548390">and</span> <span m="548600">powerful</span>
  <span m="549290">tricks</span> <span m="550220">is</span> <span m="550370">separation</span>
  <span m="551000">of</span> <span m="551060">variables.</span> <span m="552110">You</span>
  <span m="552230">need</span> <span m="552440">to</span> <span m="552560">know</span>
  <span m="552740">how</span> <span m="552920">that</span> <span m="553130">works.</span>
  <span m="555160">Then</span> <span m="555460">once</span> <span m="555760">you</span>
  <span m="556090">solve</span> <span m="556570">the</span> <span m="556690">problem,</span>
  <span m="557440">you</span> <span m="557590">have</span> <span m="557740">the</span>
  <span m="557860">general</span> <span m="558340">solution.</span> <span m="560760">And</span>
  <span m="561690">you</span> <span m="561960">then</span> <span m="562230">say,</span>
  <span m="562570">well,</span> <span m="562890">OK,</span> <span m="563730">for</span>
  <span m="563910">the</span> <span m="564060">specific</span> <span m="564720">case</span>
  <span m="565170">we</span> <span m="565410">have,</span> <span m="566430">like</span>
  <span m="566700">a</span> <span m="566760">string</span> <span m="567150">tied</span>
  <span m="567420">down</span> <span m="567690">at</span> <span m="567780">both</span>
  <span m="568080">ends,</span> <span m="569740">we</span> <span m="569790">have</span>
  <span m="570090">boundary</span> <span m="570600">conditions.</span> <span m="572460">And</span>
  <span m="572590">we</span> <span m="572740">impose</span> <span m="573130">those</span>
  <span m="573340">boundary</span> <span m="573730">conditions.</span></p><p><span
  m="575480">And</span> <span m="576430">then</span> <span m="577420">we</span> <span
  m="577780">have</span> <span m="578140">basically</span> <span m="578680">what</span>
  <span m="578830">we</span> <span m="578950">would</span> <span m="579070">call</span>
  <span m="579280">the</span> <span m="579400">normal</span> <span m="579820">modes</span>
  <span m="580510">of</span> <span m="580660">the</span> <span m="580750">problem.</span>
  <span m="582620">And</span> <span m="582740">then</span> <span m="583070">we</span>
  <span m="584900">would</span> <span m="585050">ask,</span> <span m="585380">OK,</span>
  <span m="585800">well,</span> <span m="585980">suppose</span> <span m="586550">we're</span>
  <span m="586700">doing</span> <span m="587600">a</span> <span m="587690">specific</span>
  <span m="590990">experiment</span> <span m="591710">or</span> <span m="591860">doing</span>
  <span m="592670">a</span> <span m="593030">specific</span> <span m="594080">preparation</span>
  <span m="594740">of</span> <span m="594860">the</span> <span m="594950">system.</span>
  <span m="596660">And</span> <span m="597380">we</span> <span m="597530">can</span>
  <span m="597680">call</span> <span m="597890">that</span> <span m="598070">the</span>
  <span m="598190">pluck</span> <span m="598520">of</span> <span m="598640">the</span>
  <span m="598760">system.</span> <span m="599850">And</span> <span m="600140">you</span>
  <span m="600260">might</span> <span m="600560">pluck</span> <span m="601070">several</span>
  <span m="602900">normal</span> <span m="603260">modes.</span></p><p><span m="604400">You</span>
  <span m="604520">get</span> <span m="604670">a</span> <span m="604730">superposition</span>
  <span m="605570">state.</span> <span m="606430">And</span> <span m="606530">that</span>
  <span m="606740">superposition</span> <span m="607490">state</span> <span m="608390">behaves</span>
  <span m="609200">in</span> <span m="609350">a</span> <span m="609410">dynamic</span>
  <span m="610040">way.</span> <span m="612170">And</span> <span m="612470">you</span>
  <span m="612590">want</span> <span m="612800">to</span> <span m="612860">be</span>
  <span m="612990">able</span> <span m="613090">to</span> <span m="613190">understand</span>
  <span m="613820">that</span> <span m="614030">dynamics.</span> <span m="615500">And</span>
  <span m="615650">the</span> <span m="615740">most</span> <span m="616100">important</span>
  <span m="616580">thing</span> <span m="617000">that</span> <span m="617180">I</span>
  <span m="617300">want</span> <span m="617540">you</span> <span m="617600">to</span>
  <span m="617720">do</span> <span m="619010">is,</span> <span m="619160">instead</span>
  <span m="619550">of</span> <span m="620570">trying</span> <span m="620960">to</span>
  <span m="621080">draw</span> <span m="621860">the</span> <span m="621980">solutions</span>
  <span m="622790">to</span> <span m="623710">a</span> <span m="623900">differential</span>
  <span m="624410">equation,</span> <span m="624920">which</span> <span m="625100">is</span>
  <span m="625220">a</span> <span m="625280">mathematical</span> <span m="626030">equation,</span>
  <span m="627200">I</span> <span m="627290">want</span> <span m="627500">you</span>
  <span m="627590">to</span> <span m="627710">draw</span> <span m="628250">cartoons,</span>
  <span m="630350">cartoons</span> <span m="631010">that</span> <span m="631190">embody</span>
  <span m="631640">your</span> <span m="631820">understanding</span> <span m="632450">of</span>
  <span m="632510">the</span> <span m="632600">problem.</span> <span m="634180">And</span>
  <span m="634330">I'm</span> <span m="634420">going</span> <span m="634540">to</span>
  <span m="634600">be</span> <span m="634690">trying</span> <span m="635020">to</span>
  <span m="635110">do</span> <span m="635290">that</span> <span m="635530">today.</span></p><p><span
  m="646624">OK.</span> <span m="647130">In</span> <span m="647260">this</span> <span
  m="647500">course,</span> <span m="647830">for</span> <span m="647990">the</span>
  <span m="648070">first</span> <span m="648400">half</span> <span m="648610">of</span>
  <span m="648670">the</span> <span m="648760">course,</span> <span m="649820">most</span>
  <span m="649990">of</span> <span m="650050">what</span> <span m="650200">we're</span>
  <span m="650350">going</span> <span m="650490">to</span> <span m="650590">be</span>
  <span m="650710">doing</span> <span m="651580">is</span> <span m="651760">solving</span>
  <span m="652630">for</span> <span m="653590">exactly</span> <span m="654400">soluble</span>
  <span m="655060">problems--</span> <span m="655590">the</span> <span m="655670">particle</span>
  <span m="656100">in</span> <span m="656190">a</span> <span m="656260">box,</span>
  <span m="657360">the</span> <span m="657400">harmonic</span> <span m="657910">oscillator,</span>
  <span m="660060">the</span> <span m="660190">rigid</span> <span m="660550">rotor,</span>
  <span m="666720">and</span> <span m="666840">the</span> <span m="666930">hydrogen</span>
  <span m="667320">atom.</span> <span m="670980">With</span> <span m="671160">these</span>
  <span m="671430">four</span> <span m="671670">problems,</span> <span m="672750">most</span>
  <span m="673230">of</span> <span m="673470">the</span> <span m="674220">things</span>
  <span m="674700">that</span> <span m="674850">we</span> <span m="675030">will</span>
  <span m="675240">encounter</span> <span m="676710">in</span> <span m="677850">quantum</span>
  <span m="678240">mechanics</span> <span m="679170">are</span> <span m="679440">somehow</span>
  <span m="679800">related</span> <span m="680280">to</span> <span m="680400">these.</span></p><p><span
  m="683924">And</span> <span m="684366">in</span> <span m="684810">the</span> <span
  m="684960">textbooks,</span> <span m="685560">they</span> <span m="685830">treat</span>
  <span m="686130">these</span> <span m="686340">things</span> <span m="686640">as</span>
  <span m="686730">sacred.</span> <span m="688140">And</span> <span m="688290">they</span>
  <span m="688620">say,</span> <span m="689110">OK,</span> <span m="689530">well,</span>
  <span m="689680">now</span> <span m="689760">that you've</span> <span m="690000">solved</span>
  <span m="690300">them,</span> <span m="690480">you</span> <span m="690630">understand</span>
  <span m="691110">quantum</span> <span m="691380">mechanics.</span> <span m="692580">But</span>
  <span m="692880">these</span> <span m="693120">are</span> <span m="693210">really</span>
  <span m="693750">tools</span> <span m="694260">for</span> <span m="694470">understanding</span>
  <span m="695160">more</span> <span m="695400">complicated</span> <span m="696060">situations.</span>
  <span m="697620">I</span> <span m="697680">mean,</span> <span m="697800">you</span>
  <span m="697920">might</span> <span m="698190">have</span> <span m="698400">a</span>
  <span m="698430">particle</span> <span m="698910">in</span> <span m="699010">a</span>
  <span m="699110">box.</span> <span m="699300">Instead</span> <span m="699630">of</span>
  <span m="700200">with</span> <span m="700380">a</span> <span m="700440">square</span>
  <span m="701940">bottom,</span> <span m="702300">it</span> <span m="702390">might</span>
  <span m="702630">have</span> <span m="702780">a</span> <span m="702840">tilted</span>
  <span m="703260">bottom.</span> <span m="704280">Or</span> <span m="704400">it</span>
  <span m="704460">might</span> <span m="704880">have</span> <span m="705150">a</span>
  <span m="705510">double</span> <span m="705780">minimum.</span></p><p><span m="707080">But</span>
  <span m="707550">if</span> <span m="707760">you</span> <span m="707910">understand</span>
  <span m="708420">that,</span> <span m="709560">you</span> <span m="710190">then</span>
  <span m="710520">can</span> <span m="710760">begin</span> <span m="711210">to</span>
  <span m="711360">build</span> <span m="711870">an</span> <span m="711990">understanding</span>
  <span m="712650">of,</span> <span m="712800">what</span> <span m="712950">are</span>
  <span m="713070">the</span> <span m="713190">things</span> <span m="714150">in</span>
  <span m="714510">the</span> <span m="714720">experiment</span> <span m="715440">that</span>
  <span m="715590">tell</span> <span m="715860">you</span> <span m="716190">about</span>
  <span m="716520">these</span> <span m="717810">distortions</span> <span m="718770">of</span>
  <span m="719010">the</span> <span m="719100">standard</span> <span m="719610">problem?</span>
  <span m="721200">And</span> <span m="721380">the</span> <span m="721470">same</span>
  <span m="721770">thing</span> <span m="721980">for</span> <span m="722160">a</span>
  <span m="722260">harmonic</span> <span m="722670">oscillator.</span> <span m="723960">Almost</span>
  <span m="724410">everything</span> <span m="724860">that's</span> <span m="725040">vibrating</span>
  <span m="725760">is</span> <span m="725940">harmonic</span> <span m="726510">approximately.</span>
  <span m="727890">But</span> <span m="728160">there's</span> <span m="728370">a</span>
  <span m="728430">little</span> <span m="728700">bit</span> <span m="728850">of</span>
  <span m="728940">distortion</span> <span m="729600">as</span> <span m="729720">you</span>
  <span m="729810">stretch</span> <span m="730140">it</span> <span m="730260">more.</span>
  <span m="731220">And</span> <span m="731340">again,</span> <span m="732030">you</span>
  <span m="732270">can</span> <span m="732510">understand</span> <span m="733170">how</span>
  <span m="733560">to</span> <span m="734100">measure</span> <span m="734640">the</span>
  <span m="734850">distortions</span> <span m="735750">from</span> <span m="736060">harmonicity</span>
  <span m="737070">by</span> <span m="737250">understanding</span> <span m="737730">the</span>
  <span m="737820">harmonic</span> <span m="738310">oscillator.</span> <span m="738890">We</span>
  <span m="739040">did</span> <span m="739280">rotor,</span> <span m="739920">H</span>
  <span m="740160">atom.</span> <span m="740400">It's</span> <span m="740520">all</span>
  <span m="740670">the</span> <span m="740760">same.</span></p><p><span m="741610">So</span>
  <span m="742020">I</span> <span m="742200">would</span> <span m="742350">like</span>
  <span m="742590">to</span> <span m="742710">tell</span> <span m="742980">you</span>
  <span m="743310">that</span> <span m="744300">these</span> <span m="744570">standard</span>
  <span m="745140">problems</span> <span m="745590">are</span> <span m="745650">really</span>
  <span m="745950">important.</span> <span m="747540">But</span> <span m="747720">nothing</span>
  <span m="748290">is</span> <span m="748470">like</span> <span m="748710">that.</span>
  <span m="750500">And</span> <span m="750750">what's</span> <span m="750990">important</span>
  <span m="751530">is</span> <span m="751710">how</span> <span m="751950">it's</span>
  <span m="752100">different</span> <span m="752550">from</span> <span m="752760">that.</span>
  <span m="754650">And</span> <span m="754820">this</span> <span m="754970">is</span>
  <span m="755090">my</span> <span m="755300">unique</span> <span m="755660">perspective.</span>
  <span m="757160">And</span> <span m="758000">you</span> <span m="758150">won't</span>
  <span m="758390">get</span> <span m="758600">that</span> <span m="758810">from</span>
  <span m="759410">McQuarrie</span> <span m="760160">or</span> <span m="760400">any</span>
  <span m="760700">textbook.</span> <span m="763030">But</span> <span m="763110">this</span>
  <span m="763290">is</span> <span m="763480">MIT.</span> <span m="765190">So</span>
  <span m="765630">there are</span> <span m="765790">templates</span> <span m="766480">for</span>
  <span m="766630">understanding</span> <span m="767230">real</span> <span m="767440">quantum</span>
  <span m="767740">mechanical</span> <span m="768160">system.</span></p><p><span m="769400">And</span>
  <span m="769600">the</span> <span m="770920">big</span> <span m="771250">thing,</span>
  <span m="772690">the</span> <span m="772780">most</span> <span m="773050">important</span>
  <span m="778420">technique</span> <span m="779800">for</span> <span m="780100">doing</span>
  <span m="780460">that</span> <span m="780910">is</span> <span m="781060">perturbation</span>
  <span m="781630">theory.</span> <span m="786270">And</span> <span m="786390">so</span>
  <span m="787500">perturbation</span> <span m="788190">theory</span> <span m="789240">is</span>
  <span m="789420">just</span> <span m="789690">a</span> <span m="789750">way</span>
  <span m="790050">of</span> <span m="790140">building</span> <span m="792000">beyond</span>
  <span m="792870">the</span> <span m="793560">oversimplification.</span> <span m="795450">And</span>
  <span m="795600">it's</span> <span m="795780">mathematically</span> <span m="796740">really</span>
  <span m="797220">ugly.</span> <span m="797820">But</span> <span m="798030">it's</span>
  <span m="798300">tremendously</span> <span m="799230">powerful.</span> <span m="800710">And</span>
  <span m="800920">it's</span> <span m="801070">where</span> <span m="801280">you</span>
  <span m="801400">get</span> <span m="801690">insight.</span></p><p><span m="803710">OK.</span>
  <span m="804620">Now,</span> <span m="805490">many</span> <span m="805820">people</span>
  <span m="806840">have</span> <span m="807050">complained</span> <span m="808310">that</span>
  <span m="808520">they</span> <span m="808700">found</span> <span m="809790">5.61</span>
  <span m="810710">hard.</span> <span m="811250">Because</span> <span m="811610">it's</span>
  <span m="811730">so</span> <span m="811970">mathematical.</span> <span m="816500">And</span>
  <span m="816650">maybe</span> <span m="816950">this</span> <span m="817160">is</span>
  <span m="817280">going</span> <span m="817460">to</span> <span m="817550">be</span>
  <span m="817670">the</span> <span m="817790">most</span> <span m="818090">mathematical</span>
  <span m="818840">lecture</span> <span m="819230">in</span> <span m="819320">the</span>
  <span m="819410">course.</span> <span m="820790">But</span> <span m="820970">I</span>
  <span m="821060">don't</span> <span m="821210">want</span> <span m="821390">it</span>
  <span m="821480">to</span> <span m="821600">be</span> <span m="821780">hard.</span>
  <span m="823310">Now,</span> <span m="824090">chemists</span> <span m="826340">usually</span>
  <span m="826880">derive</span> <span m="827600">insights</span> <span m="828140">from</span>
  <span m="828650">pictorial</span> <span m="829550">rather</span> <span m="829850">than</span>
  <span m="829970">mathematical</span> <span m="830900">views</span> <span m="831350">of</span>
  <span m="831470">a</span> <span m="831530">problem.</span></p><p><span m="835190">So</span>
  <span m="835370">what</span> <span m="835610">are</span> <span m="835790">the</span>
  <span m="835880">pictures</span> <span m="837570">that</span> <span m="837900">describe</span>
  <span m="838680">these</span> <span m="839400">differential</span> <span m="840060">equations?</span>
  <span m="840930">How</span> <span m="841230">do</span> <span m="841350">we</span>
  <span m="842280">convert</span> <span m="843210">what</span> <span m="843570">seems</span>
  <span m="843990">to</span> <span m="844110">be</span> <span m="844350">just</span>
  <span m="844740">straight</span> <span m="845190">mathematics</span> <span m="846260">to</span>
  <span m="846600">pictures</span> <span m="847080">that</span> <span m="847230">mean</span>
  <span m="847470">something</span> <span m="847800">to</span> <span m="848010">us?</span>
  <span m="848790">And</span> <span m="848940">that's</span> <span m="849270">my</span>
  <span m="849540">goal,</span> <span m="850560">to</span> <span m="850680">get</span>
  <span m="850920">you</span> <span m="851130">to</span> <span m="851370">be</span>
  <span m="851580">drawing</span> <span m="852150">freehand</span> <span m="852780">pictures</span>
  <span m="853650">that</span> <span m="853860">embody</span> <span m="854340">the</span>
  <span m="854520">important</span> <span m="855120">features</span> <span m="855900">of</span>
  <span m="856020">the</span> <span m="856110">solutions</span> <span m="856650">to</span>
  <span m="856770">the</span> <span m="856860">problems.</span></p><p><span m="859300">OK.</span>
  <span m="861060">So</span> <span m="862590">we're</span> <span m="862710">going</span>
  <span m="862840">to</span> <span m="862950">be</span> <span m="863070">looking</span>
  <span m="863460">at</span> <span m="864390">a</span> <span m="864480">differential</span>
  <span m="865050">equation.</span> <span m="865560">And</span> <span m="865650">one</span>
  <span m="865800">of</span> <span m="865890">the</span> <span m="865980">first</span>
  <span m="866280">questions</span> <span m="866790">you</span> <span m="866910">ask,</span>
  <span m="867300">well,</span> <span m="868230">where</span> <span m="868380">did</span>
  <span m="868500">that</span> <span m="868680">equation</span> <span m="869160">come</span>
  <span m="869400">from?</span> <span m="872510">And</span> <span m="872840">you're</span>
  <span m="872990">not</span> <span m="873200">going</span> <span m="873320">to</span>
  <span m="873530">derive</span> <span m="873950">a</span> <span m="874010">differential</span>
  <span m="874550">equation</span> <span m="875000">ever</span> <span m="875330">in</span>
  <span m="875450">this</span> <span m="875600">course.</span> <span m="876140">But</span>
  <span m="876770">you're</span> <span m="876920">going</span> <span m="877100">to</span>
  <span m="877190">want</span> <span m="877400">to</span> <span m="877460">think,</span>
  <span m="877760">well,</span> <span m="877990">I</span> <span m="878180">pretty</span>
  <span m="878480">much</span> <span m="878720">understand</span> <span m="879860">what's</span>
  <span m="880130">in</span> <span m="880310">this</span> <span m="880550">differential</span>
  <span m="881120">equation.</span> <span m="883850">And</span> <span m="884030">then</span>
  <span m="884510">we'll</span> <span m="884930">use</span> <span m="885440">standard</span>
  <span m="886130">methods</span> <span m="886820">for</span> <span m="887000">solving</span>
  <span m="887450">that</span> <span m="887660">equation.</span></p><p><span m="892630">And</span>
  <span m="893080">one</span> <span m="893320">such</span> <span m="893710">differential</span>
  <span m="894340">equation</span> <span m="895240">is</span> <span m="895510">this--</span>
  <span m="896830">second</span> <span m="897190">derivative</span> <span m="897640">of</span>
  <span m="897730">some</span> <span m="897970">function</span> <span m="898720">with</span>
  <span m="898900">respect</span> <span m="899890">to</span> <span m="900050">a</span>
  <span m="900100">variable</span> <span m="901390">is</span> <span m="901570">equal</span>
  <span m="901870">to</span> <span m="902460">a</span> <span m="902560">constant</span>
  <span m="903310">times</span> <span m="903580">that</span> <span m="903760">function.</span>
  <span m="905200">Now,</span> <span m="905350">that</span> <span m="905710">you</span>
  <span m="905860">know.</span> <span m="907250">You</span> <span m="907380">know</span>
  <span m="907580">sines</span> <span m="907910">and</span> <span m="908020">cosines</span>
  <span m="908440">are</span> <span m="908660">solutions</span> <span m="908975">to</span>
  <span m="909290">that.</span> <span m="909980">And</span> <span m="910130">you</span>
  <span m="910220">know</span> <span m="910400">that</span> <span m="910580">exponentials</span>
  <span m="911210">are</span> <span m="911350">solutions</span> <span m="911655">to</span>
  <span m="911960">that.</span> <span m="914890">Now,</span> <span m="915090">that</span>
  <span m="915240">pretty</span> <span m="915510">much</span> <span m="915720">takes</span>
  <span m="916020">you</span> <span m="916230">through</span> <span m="916620">a</span>
  <span m="916710">lot</span> <span m="917160">of</span> <span m="917250">problems</span>
  <span m="917730">in</span> <span m="917820">quantum</span> <span m="918120">mechanics.</span></p><p><span
  m="921340">But</span> <span m="921610">now,</span> <span m="921790">one</span> <span
  m="921970">of</span> <span m="922030">the</span> <span m="922150">important</span>
  <span m="922570">things</span> <span m="922990">is</span> <span m="923860">this</span>
  <span m="924130">is</span> <span m="924310">a</span> <span m="924850">second-order</span>
  <span m="925300">differential</span> <span m="925870">equation.</span> <span m="928010">And</span>
  <span m="928030">that</span> <span m="928210">means</span> <span m="928660">that</span>
  <span m="928840">there</span> <span m="929020">are</span> <span m="929140">going</span>
  <span m="929440">to</span> <span m="929560">be</span> <span m="929770">two</span>
  <span m="930610">linearly</span> <span m="931300">independent</span> <span m="932050">solutions.</span>
  <span m="935010">And</span> <span m="935190">you</span> <span m="935310">need</span>
  <span m="935460">to</span> <span m="935580">know</span> <span m="935730">both</span>
  <span m="936030">of</span> <span m="936090">them.</span> <span m="938490">I'll</span>
  <span m="938670">talk</span> <span m="938910">about</span> <span m="939120">this</span>
  <span m="939330">some</span> <span m="939510">more</span> <span m="939960">later.</span></p><p><span
  m="941460">Now,</span> <span m="942430">sometimes,</span> <span m="943250">the</span>
  <span m="943340">differential</span> <span m="943910">equations</span> <span m="944480">look</span>
  <span m="944780">much</span> <span m="945110">more</span> <span m="945290">complicated</span>
  <span m="945950">than</span> <span m="946130">this.</span> <span m="947210">And</span>
  <span m="947720">so</span> <span m="948740">the</span> <span m="949370">goal</span>
  <span m="950090">is</span> <span m="950750">usually</span> <span m="951170">to</span>
  <span m="951320">rewrite</span> <span m="951920">it</span> <span m="952160">in</span>
  <span m="952340">a</span> <span m="952400">form</span> <span m="953270">which</span>
  <span m="953480">corresponds</span> <span m="954350">to</span> <span m="955130">a</span>
  <span m="955220">differential</span> <span m="955790">equation</span> <span m="956270">that</span>
  <span m="956390">is</span> <span m="956900">well</span> <span m="957270">known</span>
  <span m="957650">and</span> <span m="957770">solved</span> <span m="958490">by</span>
  <span m="958640">mathematicians</span> <span m="960200">whose</span> <span m="960380">business</span>
  <span m="960830">is</span> <span m="961280">doing</span> <span m="961580">that.</span>
  <span m="962650">But</span> <span m="962810">we</span> <span m="962990">won't</span>
  <span m="963230">be</span> <span m="963350">doing</span> <span m="963620">that.</span></p><p><span
  m="966100">OK.</span> <span m="968140">But</span> <span m="968390">usually,</span>
  <span m="969650">when</span> <span m="969830">you</span> <span m="969950">have</span>
  <span m="970280">a</span> <span m="970340">differential</span> <span m="970910">equation,</span>
  <span m="972590">the</span> <span m="972740">function</span> <span m="973670">is</span>
  <span m="974330">of</span> <span m="974690">more</span> <span m="974990">than</span>
  <span m="975170">one</span> <span m="975380">variable.</span> <span m="976400">And</span>
  <span m="976490">frequently,</span> <span m="977090">it's</span> <span m="977270">position</span>
  <span m="977720">and</span> <span m="977840">time.</span> <span m="978990">And</span>
  <span m="979100">so</span> <span m="979490">the</span> <span m="979610">first</span>
  <span m="979970">thing</span> <span m="980180">you</span> <span m="980300">do</span>
  <span m="981200">is</span> <span m="981350">you</span> <span m="981470">try</span>
  <span m="981800">to</span> <span m="981890">separate</span> <span m="982400">variables.</span>
  <span m="983570">And</span> <span m="983660">so</span> <span m="983990">that's</span>
  <span m="984200">what</span> <span m="984320">we're</span> <span m="984410">going</span>
  <span m="984550">to</span> <span m="984630">do.</span></p><p><span m="988380">So</span>
  <span m="988490">we</span> <span m="988640">have</span> <span m="988790">a</span>
  <span m="988850">differential</span> <span m="989450">equation.</span> <span m="992250">And</span>
  <span m="993440">the</span> <span m="993530">first</span> <span m="993830">thing</span>
  <span m="994100">is</span> <span m="994730">a</span> <span m="994790">general</span>
  <span m="995210">solution.</span> <span m="1001260">And</span> <span m="1002630">one</span>
  <span m="1002780">of</span> <span m="1002870">the</span> <span m="1002960">things</span>
  <span m="1003440">that</span> <span m="1003650">this</span> <span m="1004010">solution</span>
  <span m="1004490">will</span> <span m="1004640">have</span> <span m="1005300">is</span>
  <span m="1005450">nodes.</span> <span m="1007270">And</span> <span m="1008350">the</span>
  <span m="1008470">distance</span> <span m="1009280">between</span> <span m="1009790">nodes--</span>
  <span m="1013130">here's</span> <span m="1013270">a</span> <span m="1013330">node.</span>
  <span m="1013630">Here's</span> <span m="1013810">a</span> <span m="1013910">node.</span>
  <span m="1014680">That's</span> <span m="1016630">half</span> <span m="1016900">the</span>
  <span m="1016990">wavelength.</span> <span m="1019160">And</span> <span m="1019310">we</span>
  <span m="1019460">know</span> <span m="1019970">that</span> <span m="1020690">in</span>
  <span m="1020840">quantum</span> <span m="1021140">mechanics,</span> <span m="1021650">if</span>
  <span m="1021770">you</span> <span m="1021890">know</span> <span m="1022040">the</span>
  <span m="1022130">wavelength,</span> <span m="1022640">you</span> <span m="1022700">know</span>
  <span m="1022850">the</span> <span m="1022970">momentum.</span> <span m="1025400">So</span>
  <span m="1025619">nodes</span> <span m="1026040">are</span> <span m="1026099">really</span>
  <span m="1026520">important.</span> <span m="1027000">Because</span> <span m="1027329">it's</span>
  <span m="1027480">telling</span> <span m="1027810">you</span> <span m="1027960">how</span>
  <span m="1028140">fast</span> <span m="1028470">things</span> <span m="1028710">are</span>
  <span m="1028770">moving.</span></p><p><span m="1032220">We</span> <span m="1032339">can</span>
  <span m="1032550">also</span> <span m="1033690">look</span> <span m="1033869">at</span>
  <span m="1033960">the</span> <span m="1034109">envelope.</span> <span m="1037109">And</span>
  <span m="1037200">this</span> <span m="1037380">would</span> <span m="1037560">be</span>
  <span m="1037740">some</span> <span m="1037980">kind</span> <span m="1038220">of</span>
  <span m="1038369">classical,</span> <span m="1039270">as</span> <span m="1039420">opposed</span>
  <span m="1039750">to</span> <span m="1039869">a</span> <span m="1040020">quantum</span>
  <span m="1040410">mechanical,</span> <span m="1041400">probability</span> <span
  m="1042210">distribution.</span> <span m="1043780">And</span> <span m="1043800">so</span>
  <span m="1044960">it</span> <span m="1045569">might</span> <span m="1045810">look</span>
  <span m="1047160">like</span> <span m="1047490">this.</span> <span m="1049470">But</span>
  <span m="1049710">the</span> <span m="1049890">important</span> <span m="1050280">thing</span>
  <span m="1050610">about</span> <span m="1050910">the</span> <span m="1051060">envelope</span>
  <span m="1051720">is</span> <span m="1051840">that</span> <span m="1051990">it's</span>
  <span m="1052170">always</span> <span m="1052560">positive.</span> <span m="1053250">Because</span>
  <span m="1053580">it's</span> <span m="1053730">probability,</span> <span m="1055290">as</span>
  <span m="1055440">opposed</span> <span m="1055770">to</span> <span m="1055930">a</span>
  <span m="1055950">probability</span> <span m="1056760">amplitude,</span> <span m="1058030">which</span>
  <span m="1058200">can</span> <span m="1058350">be</span> <span m="1058500">positive</span>
  <span m="1059100">and</span> <span m="1059190">negative.</span> <span m="1061610">Interference</span>
  <span m="1062330">is</span> <span m="1062540">really</span> <span m="1062900">important</span>
  <span m="1063290">in</span> <span m="1063380">quantum</span> <span m="1063680">mechanics.</span>
  <span m="1064280">But</span> <span m="1064580">sometimes,</span> <span m="1065060">the</span>
  <span m="1065180">envelope</span> <span m="1065720">tells</span> <span m="1065990">you</span>
  <span m="1066080">all</span> <span m="1066260">you</span> <span m="1066380">need</span>
  <span m="1066530">to</span> <span m="1066650">know.</span></p><p><span m="1069350">And</span>
  <span m="1069470">the</span> <span m="1069620">other</span> <span m="1069830">thing</span>
  <span m="1070130">is</span> <span m="1070850">the</span> <span m="1071000">velocity</span>
  <span m="1073810">of</span> <span m="1074270">a</span> <span m="1074330">stationary</span>
  <span m="1076220">phase.</span> <span m="1080550">So</span> <span m="1080630">you</span>
  <span m="1080750">have</span> <span m="1080930">a</span> <span m="1080990">wave.</span>
  <span m="1081470">And</span> <span m="1081590">it's</span> <span m="1081740">moving.</span>
  <span m="1082340">And</span> <span m="1082460">you</span> <span m="1082580">sit</span>
  <span m="1082870">at</span> <span m="1082950">a</span> <span m="1083110">point</span>
  <span m="1083600">on</span> <span m="1083730">that</span> <span m="1083990">wave.</span>
  <span m="1084380">And</span> <span m="1084530">you</span> <span m="1084650">ask,</span>
  <span m="1084890">how</span> <span m="1085010">fast</span> <span m="1085310">does</span>
  <span m="1085460">that</span> <span m="1085610">point</span> <span m="1085940">move?</span>
  <span m="1087390">And</span> <span m="1087750">I</span> <span m="1087870">did</span>
  <span m="1088080">that</span> <span m="1088320">last</span> <span m="1088590">time.</span>
  <span m="1089700">And</span> <span m="1090070">OK.</span> <span m="1093390">So</span>
  <span m="1095070">I've</span> <span m="1095220">already</span> <span m="1095430">talked</span>
  <span m="1095760">a</span> <span m="1095820">little</span> <span m="1096030">bit</span>
  <span m="1096210">about</span> <span m="1098280">what</span> <span m="1098520">we</span>
  <span m="1098640">do</span> <span m="1099060">next.</span></p><p><span m="1099390">But</span>
  <span m="1099570">the</span> <span m="1099720">important</span> <span m="1100170">thing</span>
  <span m="1100530">is</span> <span m="1100770">always,</span> <span m="1101910">at</span>
  <span m="1102090">the</span> <span m="1102330">end,</span> <span m="1103140">you</span>
  <span m="1103260">draw</span> <span m="1103650">a</span> <span m="1103710">cartoon.</span>
  <span m="1104880">And</span> <span m="1105030">you</span> <span m="1107430">endow</span>
  <span m="1107880">that</span> <span m="1108090">cartoon</span> <span m="1109080">with</span>
  <span m="1109260">your</span> <span m="1109410">insights.</span> <span m="1111060">And</span>
  <span m="1111210">that</span> <span m="1111510">enables</span> <span m="1111930">you</span>
  <span m="1112020">to</span> <span m="1112080">remember</span> <span m="1113700">and</span>
  <span m="1113880">to</span> <span m="1114030">understand</span> <span m="1115320">and</span>
  <span m="1115470">to</span> <span m="1115590">organize</span> <span m="1116100">questions</span>
  <span m="1116580">about</span> <span m="1116790">the</span> <span m="1116880">problem.</span>
  <span m="1120640">OK.</span> <span m="1121480">So</span> <span m="1121660">let's</span>
  <span m="1121870">get</span> <span m="1122050">to</span> <span m="1122170">work</span>
  <span m="1122500">on</span> <span m="1122620">a</span> <span m="1122650">real</span>
  <span m="1122890">problem.</span></p><p><span m="1131820">So</span> <span m="1132440">we</span>
  <span m="1132620">have</span> <span m="1133880">a</span> <span m="1133970">string</span>
  <span m="1135210">that's</span> <span m="1135470">tied</span> <span m="1135740">down</span>
  <span m="1136030">to</span> <span m="1136100">two</span> <span m="1136310">points.</span>
  <span m="1138020">And</span> <span m="1139460">so</span> <span m="1141770">let's</span>
  <span m="1142490">look</span> <span m="1142760">at</span> <span m="1143520">the</span>
  <span m="1143920">distortion</span> <span m="1144650">of</span> <span m="1144830">that</span>
  <span m="1145220">string.</span> <span m="1146600">And</span> <span m="1147200">so</span>
  <span m="1147440">we</span> <span m="1147740">chop</span> <span m="1148130">this</span>
  <span m="1148700">region</span> <span m="1149150">of</span> <span m="1149330">space</span>
  <span m="1149780">up</span> <span m="1150470">into</span> <span m="1152130">regions.</span>
  <span m="1155670">So</span> <span m="1155930">this</span> <span m="1156200">might</span>
  <span m="1156470">be</span> <span m="1157610">the</span> <span m="1157760">region</span>
  <span m="1158150">at</span> <span m="1159050">x</span> <span m="1159500">minus</span>
  <span m="1159980">1.</span> <span m="1160460">And this</span> <span m="1160670">might</span>
  <span m="1160910">be</span> <span m="1161030">the</span> <span m="1161120">region</span>
  <span m="1161420">at</span> <span m="1161540">x0.</span> <span m="1162230">And</span>
  <span m="1162560">this</span> <span m="1162770">might</span> <span m="1163040">be</span>
  <span m="1163200">the</span> <span m="1163220">region</span> <span m="1163670">of</span>
  <span m="1163790">x1.</span></p><p><span m="1166100">And</span> <span m="1166460">we're</span>
  <span m="1166820">interested</span> <span m="1167570">in--</span> <span m="1168270">OK,</span>
  <span m="1169340">suppose</span> <span m="1169850">we</span> <span m="1170030">have</span>
  <span m="1170900">the</span> <span m="1171020">value</span> <span m="1171530">of</span>
  <span m="1171710">the</span> <span m="1171830">displacement</span> <span m="1173090">of</span>
  <span m="1173360">the</span> <span m="1174980">wave</span> <span m="1176150">here</span>
  <span m="1177980">at</span> <span m="1178310">x</span> <span m="1178520">minus 1</span>
  <span m="1178890">and</span> <span m="1179277">here</span> <span m="1181030">and</span>
  <span m="1181190">here.</span> <span m="1182410">OK,</span> <span m="1182880">so</span>
  <span m="1182990">these</span> <span m="1183290">would</span> <span m="1183470">be</span>
  <span m="1184040">the</span> <span m="1184580">amount</span> <span m="1185120">that</span>
  <span m="1185330">the</span> <span m="1185420">wave</span> <span m="1185780">is</span>
  <span m="1185930">displaced</span> <span m="1186680">from</span> <span m="1186980">equilibrium.</span>
  <span m="1188560">And</span> <span m="1189470">we</span> <span m="1189620">call</span>
  <span m="1190010">those</span> <span m="1191750">u</span> <span m="1192110">of</span>
  <span m="1192920">x.</span></p><p><span m="1195820">And</span> <span m="1197620">so</span>
  <span m="1199450">the</span> <span m="1199570">first</span> <span m="1200170">segment</span>
  <span m="1200650">here,</span> <span m="1200890">the</span> <span m="1201100">minus
  1</span> <span m="1201490">segment,</span> <span m="1203230">this</span> <span m="1203710">segment</span>
  <span m="1205440">is</span> <span m="1205620">pulling</span> <span m="1206040">down</span>
  <span m="1206570">on</span> <span m="1207090">this</span> <span m="1207270">segment</span>
  <span m="1207660">of</span> <span m="1207720">the</span> <span m="1207870">string</span>
  <span m="1208770">by</span> <span m="1209040">this</span> <span m="1209280">amount.</span>
  <span m="1211180">And</span> <span m="1211230">this</span> <span m="1211410">one</span>
  <span m="1211620">is</span> <span m="1212070">pulling</span> <span m="1212610">up</span>
  <span m="1214070">on</span> <span m="1214710">the</span> <span m="1214830">segment</span>
  <span m="1215280">by</span> <span m="1215490">that</span> <span m="1215700">amount.</span>
  <span m="1217260">So</span> <span m="1217430">we</span> <span m="1217640">want</span>
  <span m="1217820">to</span> <span m="1217880">know,</span> <span m="1218090">what</span>
  <span m="1218270">is</span> <span m="1218420">the</span> <span m="1218510">force</span>
  <span m="1220240">acting</span> <span m="1220580">on</span> <span m="1220780">each</span>
  <span m="1221080">segment?</span> <span m="1222650">And</span> <span m="1222920">so</span>
  <span m="1225410">we</span> <span m="1226970">have</span> <span m="1227930">the</span>
  <span m="1228260">force</span> <span m="1228680">constant</span> <span m="1229730">times</span>
  <span m="1230240">the</span> <span m="1230580">displacement</span> <span m="1231990">at</span>
  <span m="1232640">x0</span> <span m="1233900">minus</span> <span m="1234530">the</span>
  <span m="1234620">displacement</span> <span m="1235690">at</span> <span m="1235970">x</span>
  <span m="1236245">minus</span> <span m="1236520">1.</span> <span m="1236930">So</span>
  <span m="1237140">this</span> <span m="1237380">is</span> <span m="1237590">the</span>
  <span m="1237710">difference</span> <span m="1238700">between</span> <span m="1239120">the</span>
  <span m="1239260">displacements.</span> <span m="1240360">And</span> <span m="1240470">this</span>
  <span m="1240620">is</span> <span m="1240770">the</span> <span m="1240860">force</span>
  <span m="1241220">constant.</span> <span m="1241730">We're</span> <span m="1241910">talking</span>
  <span m="1242330">about</span> <span m="1242600">Hooke's</span> <span m="1242910">law.</span>
  <span m="1244530">Hooke's</span> <span m="1244780">law</span> <span m="1245770">is</span>
  <span m="1246190">the</span> <span m="1246280">force</span> <span m="1247630">is</span>
  <span m="1247780">equal</span> <span m="1248050">to</span> <span m="1248140">minus</span>
  <span m="1248830">k</span> <span m="1249550">times</span> <span m="1249970">the</span>
  <span m="1250060">displacement.</span></p><p><span m="1254070">And</span> <span
  m="1254190">so</span> <span m="1256880">we</span> <span m="1257030">collect</span>
  <span m="1257300">the</span> <span m="1257480">forces</span> <span m="1257990">felt</span>
  <span m="1258290">by</span> <span m="1258680">each</span> <span m="1259010">particle.</span>
  <span m="1260270">And</span> <span m="1260810">the</span> <span m="1261230">forces</span>
  <span m="1261770">felt</span> <span m="1262070">by</span> <span m="1262280">each</span>
  <span m="1262460">particle</span> <span m="1263340">are,</span> <span m="1263660">again,</span>
  <span m="1264160">the</span> <span m="1266330">force</span> <span m="1266690">constant</span>
  <span m="1267950">times</span> <span m="1268610">the</span> <span m="1268790">difference</span>
  <span m="1269630">in</span> <span m="1271070">u</span> <span m="1271430">at</span>
  <span m="1271530">0</span> <span m="1272600">and</span> <span m="1273650">minus</span>
  <span m="1274010">1</span> <span m="1275360">minus</span> <span m="1276170">the</span>
  <span m="1276350">difference--</span> <span m="1277730">plus</span> <span m="1278030">1</span>
  <span m="1278660">minus</span> <span m="1279110">the</span> <span m="1279200">difference</span>
  <span m="1280070">in</span> <span m="1280220">u</span> <span m="1280430">at</span>
  <span m="1280580">0</span> <span m="1281810">and</span> <span m="1282294">plus</span>
  <span m="1282778">1.</span> <span m="1283746">And</span> <span m="1284230">this</span>
  <span m="1284470">is</span> <span m="1284620">a</span> <span m="1284680">second</span>
  <span m="1285040">derivative.</span> <span m="1287400">This</span> <span m="1287550">is</span>
  <span m="1287640">the</span> <span m="1287730">second</span> <span m="1288090">derivative</span>
  <span m="1289200">of</span> <span m="1289320">u</span> <span m="1289590">with</span>
  <span m="1289740">respect</span> <span m="1290220">to</span> <span m="1290320">x.</span></p><p><span
  m="1292520">So</span> <span m="1292820">we've</span> <span m="1293060">derived</span>
  <span m="1294140">a</span> <span m="1294200">wave</span> <span m="1294470">equation.</span>
  <span m="1296310">And</span> <span m="1297170">we</span> <span m="1297320">know</span>
  <span m="1297620">it's</span> <span m="1297800">going</span> <span m="1297980">to</span>
  <span m="1298060">involve</span> <span m="1298450">a</span> <span m="1298520">second</span>
  <span m="1298850">derivative.</span> <span m="1299450">So</span> <span m="1300920">force</span>
  <span m="1301270">is</span> <span m="1301430">equal</span> <span m="1301700">to</span>
  <span m="1301820">mass</span> <span m="1302210">times</span> <span m="1302600">acceleration.</span>
  <span m="1303990">Well,</span> <span m="1304100">we</span> <span m="1304250">already</span>
  <span m="1304550">know</span> <span m="1305270">the</span> <span m="1305390">force</span>
  <span m="1306620">is</span> <span m="1306950">going</span> <span m="1307250">to</span>
  <span m="1307400">be</span> <span m="1308510">related</span> <span m="1309050">to</span>
  <span m="1310370">the</span> <span m="1310490">second</span> <span m="1310820">derivative</span>
  <span m="1311910">of</span> <span m="1313240">u</span> <span m="1313610">with</span>
  <span m="1313820">respect</span> <span m="1314290">to</span> <span m="1314450">x.</span>
  <span m="1317030">And</span> <span m="1317180">now,</span> <span m="1317360">this</span>
  <span m="1317570">is</span> <span m="1317930">something.</span> <span m="1318860">And</span>
  <span m="1319280">we</span> <span m="1319430">know</span> <span m="1319650">what</span>
  <span m="1320130">this</span> <span m="1320610">is.</span> <span m="1321320">This</span>
  <span m="1321590">is</span> <span m="1321710">going</span> <span m="1321890">to</span>
  <span m="1321950">be</span> <span m="1322040">the</span> <span m="1322160">time</span>
  <span m="1322520">derivative.</span></p><p><span m="1328390">OK.</span> <span m="1328900">And</span>
  <span m="1329050">this</span> <span m="1329290">is</span> <span m="1329440">just</span>
  <span m="1329650">something</span> <span m="1330160">that</span> <span m="1330310">gets</span>
  <span m="1330580">the</span> <span m="1330670">units</span> <span m="1331000">right.</span>
  <span m="1335160">And</span> <span m="1336690">it</span> <span m="1336990">has</span>
  <span m="1337260">physical</span> <span m="1337830">significance.</span> <span m="1338610">But</span>
  <span m="1339330">in</span> <span m="1339960">the</span> <span m="1340050">case</span>
  <span m="1340470">of</span> <span m="1340650">this</span> <span m="1340890">particle</span>
  <span m="1341400">on</span> <span m="1341550">a</span> <span m="1341610">string--</span>
  <span m="1342490">this</span> <span m="1343530">wave</span> <span m="1343890">on</span>
  <span m="1344040">a</span> <span m="1344100">string,</span> <span m="1345090">it's</span>
  <span m="1345300">related</span> <span m="1345690">to</span> <span m="1345840">the</span>
  <span m="1346020">mass</span> <span m="1346500">of</span> <span m="1346590">the</span>
  <span m="1346710">string</span> <span m="1347760">and</span> <span m="1347880">the</span>
  <span m="1347970">tension</span> <span m="1348420">of</span> <span m="1348540">the</span>
  <span m="1348630">string.</span> <span m="1351780">And</span> <span m="1351930">it's</span>
  <span m="1352080">also</span> <span m="1352650">related</span> <span m="1353060">to</span>
  <span m="1353150">the</span> <span m="1353280">velocity</span> <span m="1353970">that</span>
  <span m="1354150">things</span> <span m="1354480">move.</span></p><p><span m="1356020">OK.</span>
  <span m="1356320">So</span> <span m="1356470">we</span> <span m="1356590">have</span>
  <span m="1356800">a</span> <span m="1356860">differential</span> <span m="1357430">equation</span>
  <span m="1358600">that</span> <span m="1358780">is</span> <span m="1358960">related</span>
  <span m="1359350">to</span> <span m="1359530">forces</span> <span m="1359980">equal</span>
  <span m="1360220">to</span> <span m="1360370">mass</span> <span m="1360640">times</span>
  <span m="1361040">acceleration.</span> <span m="1362200">And</span> <span m="1362530">the</span>
  <span m="1363070">differential</span> <span m="1363580">equation</span> <span m="1364660">has</span>
  <span m="1364870">the</span> <span m="1364990">form</span> <span m="1366030">second</span>
  <span m="1366773">derivative</span> <span m="1367126">of</span> <span m="1367480">u</span>
  <span m="1368200">with</span> <span m="1368350">respect</span> <span m="1369700">to</span>
  <span m="1371980">x</span> <span m="1375220">is</span> <span m="1375370">equal</span>
  <span m="1375610">to</span> <span m="1375760">1</span> <span m="1376030">over</span>
  <span m="1376360">v</span> <span m="1376720">squared</span> <span m="1379130">times</span>
  <span m="1379560">the</span> <span m="1379640">second</span> <span m="1380000">derivative</span>
  <span m="1381190">of</span> <span m="1381340">u</span> <span m="1381980">with</span>
  <span m="1382190">respect</span> <span m="1383150">to</span> <span m="1383330">t.</span>
  <span m="1385540">That's</span> <span m="1385840">the</span> <span m="1385930">wave</span>
  <span m="1386180">equation.</span></p><p><span m="1388880">So</span> <span m="1389110">it</span>
  <span m="1389690">is</span> <span m="1390040">really</span> <span m="1390730">f</span>
  <span m="1391030">is</span> <span m="1391210">equal</span> <span m="1391450">to</span>
  <span m="1391510">ma.</span> <span m="1392260">But</span> <span m="1393020">OK.</span>
  <span m="1393790">And</span> <span m="1393910">now,</span> <span m="1394150">the</span>
  <span m="1394300">units</span> <span m="1394870">of</span> <span m="1395020">this--</span>
  <span m="1395820">this</span> <span m="1396220">is</span> <span m="1396370">x.</span>
  <span m="1397230">And</span> <span m="1397330">this</span> <span m="1397510">is</span>
  <span m="1397630">t.</span> <span m="1398110">In</span> <span m="1398260">order</span>
  <span m="1398440">to</span> <span m="1398590">be</span> <span m="1398740">dimensionally</span>
  <span m="1399370">consistent,</span> <span m="1400480">this</span> <span m="1400630">has</span>
  <span m="1400870">to</span> <span m="1401020">be</span> <span m="1402430">something</span>
  <span m="1402940">that</span> <span m="1403120">is</span> <span m="1404665">x</span>
  <span m="1405010">over</span> <span m="1405190">t,</span> <span m="1406675">OK?</span>
  <span m="1407080">And</span> <span m="1407660">so</span> <span m="1408560">this</span>
  <span m="1408740">may</span> <span m="1408990">be</span> <span m="1409110">a</span>
  <span m="1409190">velocity.</span> <span m="1409700">But</span> <span m="1409820">it</span>
  <span m="1409880">has</span> <span m="1410030">units</span> <span m="1410390">of</span>
  <span m="1410450">velocity.</span> <span m="1411150">That's</span> <span m="1411320">the</span>
  <span m="1411440">differential</span> <span m="1412010">equation</span> <span m="1412850">we</span>
  <span m="1412970">want</span> <span m="1413180">to</span> <span m="1413300">solve.</span></p><p><span
  m="1417400">OK.</span> <span m="1418170">Well,</span> <span m="1418620">the</span>
  <span m="1419400">original</span> <span m="1419940">differential</span> <span m="1420540">equation</span>
  <span m="1421020">that</span> <span m="1421140">I</span> <span m="1421260">wrote--</span>
  <span m="1428020">but</span> <span m="1428260">I'm</span> <span m="1428620">getting</span>
  <span m="1428950">ahead</span> <span m="1429100">of</span> <span m="1429160">myself.</span>
  <span m="1429640">OK.</span> <span m="1430480">So</span> <span m="1431590">this</span>
  <span m="1431860">U</span> <span m="1432610">of</span> <span m="1432790">x</span>
  <span m="1433110">and</span> <span m="1433540">t--</span> <span m="1436590">we'd</span>
  <span m="1436800">like</span> <span m="1437130">it</span> <span m="1437250">to</span>
  <span m="1437400">be</span> <span m="1438540">X</span> <span m="1438930">of</span>
  <span m="1439080">x</span> <span m="1440670">times</span> <span m="1441210">T</span>
  <span m="1441460">of</span> <span m="1441890">t.</span> <span m="1443280">We</span>
  <span m="1443430">think</span> <span m="1444000">we</span> <span m="1444210">could</span>
  <span m="1444390">separate</span> <span m="1444930">the</span> <span m="1445020">variables</span>
  <span m="1445620">in</span> <span m="1445740">this</span> <span m="1445950">way.</span>
  <span m="1447780">So</span> <span m="1447900">we</span> <span m="1448020">try</span>
  <span m="1448350">it.</span> <span m="1448950">If</span> <span m="1449160">we</span>
  <span m="1449340">fail,</span> <span m="1450360">it</span> <span m="1450480">says</span>
  <span m="1450900">you</span> <span m="1450990">can't</span> <span m="1451260">do</span>
  <span m="1451440">that.</span> <span m="1453050">Failure</span> <span m="1453590">is</span>
  <span m="1453740">usually</span> <span m="1454220">going</span> <span m="1454550">to</span>
  <span m="1454670">be</span> <span m="1455350">a</span> <span m="1456170">result</span>
  <span m="1456980">that</span> <span m="1457780">the</span> <span m="1458810">solution</span>
  <span m="1459440">to</span> <span m="1459560">the</span> <span m="1459680">differential</span>
  <span m="1460250">equation</span> <span m="1460670">in</span> <span m="1460760">this</span>
  <span m="1460970">form</span> <span m="1461360">is</span> <span m="1461720">nothing.</span>
  <span m="1462200">It's</span> <span m="1462320">a</span> <span m="1462380">straight</span>
  <span m="1462680">line.</span> <span m="1463440">Nothing's</span> <span m="1463810">happening.</span>
  <span m="1465770">So</span> <span m="1466060">failure</span> <span m="1466600">is</span>
  <span m="1467410">acceptable.</span> <span m="1468290">But</span> <span m="1468460">if</span>
  <span m="1470560">we're</span> <span m="1470740">successful,</span> <span m="1471400">we're</span>
  <span m="1471580">going</span> <span m="1471730">to</span> <span m="1471820">get</span>
  <span m="1472000">two</span> <span m="1472300">separate</span> <span m="1472750">differential</span>
  <span m="1473350">equations.</span></p><p><span m="1476100">OK.</span> <span m="1476610">So</span>
  <span m="1477120">what</span> <span m="1477360">we</span> <span m="1477480">do</span>
  <span m="1477780">then</span> <span m="1478050">is</span> <span m="1478230">take</span>
  <span m="1478590">this</span> <span m="1478920">differential</span> <span m="1479520">equation,</span>
  <span m="1482690">substitute</span> <span m="1483220">this</span> <span m="1483520">in,</span>
  <span m="1484240">and</span> <span m="1484390">divide</span> <span m="1484870">on</span>
  <span m="1485020">the</span> <span m="1485080">left.</span> <span m="1485480">So</span>
  <span m="1485530">we</span> <span m="1485680">have</span> <span m="1486250">1</span>
  <span m="1486490">over</span> <span m="1487150">X</span> <span m="1488000">of</span>
  <span m="1489140">x</span> <span m="1491710">times</span> <span m="1492040">T</span>
  <span m="1492385">of</span> <span m="1492730">t</span> <span m="1493870">times</span>
  <span m="1494650">the</span> <span m="1494740">second</span> <span m="1495070">derivative</span>
  <span m="1496820">with</span> <span m="1496930">respect</span> <span m="1497680">to</span>
  <span m="1497800">x</span> <span m="1499210">of</span> <span m="1500170">xt</span>
  <span m="1502150">is</span> <span m="1502330">equal</span> <span m="1502600">to</span>
  <span m="1503260">1</span> <span m="1503500">over</span> <span m="1504400">xt</span>
  <span m="1506720">times</span> <span m="1507470">the</span> <span m="1507590">second</span>
  <span m="1508520">derivative</span> <span m="1509750">with</span> <span m="1509930">respect</span>
  <span m="1510740">to</span> <span m="1511160">t</span> <span m="1512090">of</span>
  <span m="1512830">xt.</span></p><p><span m="1516360">OK.</span> <span m="1518610">Well,</span>
  <span m="1522060">on</span> <span m="1522210">this</span> <span m="1522360">side</span>
  <span m="1522690">of</span> <span m="1522750">the</span> <span m="1522900">equation,</span>
  <span m="1524190">the</span> <span m="1524340">only</span> <span m="1524610">thing</span>
  <span m="1524820">that</span> <span m="1524970">involves</span> <span m="1525390">time</span>
  <span m="1526230">is</span> <span m="1526440">here.</span> <span m="1527710">This</span>
  <span m="1527790">doesn't</span> <span m="1528090">operate</span> <span m="1528510">on</span>
  <span m="1528630">time.</span> <span m="1529440">And</span> <span m="1529590">so</span>
  <span m="1529800">we</span> <span m="1529980">can</span> <span m="1530160">cancel</span>
  <span m="1531240">the</span> <span m="1531390">time</span> <span m="1531750">dependence</span>
  <span m="1532560">from</span> <span m="1532770">this</span> <span m="1532920">side.</span>
  <span m="1535560">And</span> <span m="1535680">over</span> <span m="1535920">on</span>
  <span m="1536040">this</span> <span m="1536190">side,</span> <span m="1537240">this</span>
  <span m="1537540">derivative</span> <span m="1540490">operates</span> <span m="1541000">on</span>
  <span m="1541120">t</span> <span m="1541360">but</span> <span m="1541510">not</span>
  <span m="1541780">x.</span> <span m="1542620">And</span> <span m="1542710">so</span>
  <span m="1542860">we</span> <span m="1542980">can</span> <span m="1543160">cancel</span>
  <span m="1544180">the</span> <span m="1544360">x</span> <span m="1544660">part.</span>
  <span m="1545890">And</span> <span m="1546010">so</span> <span m="1546220">what</span>
  <span m="1546340">we</span> <span m="1546520">have</span> <span m="1547030">now</span>
  <span m="1547870">is</span> <span m="1548230">an</span> <span m="1548740">equation</span>
  <span m="1550150">X</span> <span m="1550780">of</span> <span m="1551050">x</span>
  <span m="1552970">second</span> <span m="1553300">derivative</span> <span m="1554710">with</span>
  <span m="1554890">respect</span> <span m="1555340">to</span> <span m="1555440">x</span>
  <span m="1555520">squared</span> <span m="1556310">of</span> <span m="1556560">x</span>
  <span m="1557830">is</span> <span m="1558010">equal</span> <span m="1558370">to</span>
  <span m="1561700">this</span> <span m="1561970">constant,</span> <span m="1562510">1</span>
  <span m="1562720">over</span> <span m="1562930">v</span> <span m="1563110">squared,</span>
  <span m="1564640">times</span> <span m="1567360">1</span> <span m="1567640">over</span>
  <span m="1567880">t</span> <span m="1568780">times</span> <span m="1569170">the</span>
  <span m="1569560">derivative</span> <span m="1570520">of</span> <span m="1570670">T</span>
  <span m="1571390">with</span> <span m="1571550">respect</span> <span m="1571940">to</span>
  <span m="1572050">little</span> <span m="1572290">t,</span> <span m="1574580">OK?</span></p><p><span
  m="1575630">So</span> <span m="1575810">this</span> <span m="1576020">is</span>
  <span m="1576500">interesting.</span> <span m="1577550">We</span> <span m="1577670">have</span>
  <span m="1577940">a</span> <span m="1578030">function</span> <span m="1578480">of</span>
  <span m="1578600">x</span> <span m="1578930">on</span> <span m="1579020">this</span>
  <span m="1579200">side</span> <span m="1580600">and</span> <span m="1580730">a</span>
  <span m="1580790">function</span> <span m="1581210">of</span> <span m="1581300">t</span>
  <span m="1581690">on</span> <span m="1581810">this</span> <span m="1581970">side.</span>
  <span m="1583330">They</span> <span m="1583560">are</span> <span m="1583680">independent</span>
  <span m="1584250">variables.</span> <span m="1585510">This</span> <span m="1585750">can</span>
  <span m="1585960">only</span> <span m="1586230">be</span> <span m="1586410">true</span>
  <span m="1586890">if</span> <span m="1587070">both</span> <span m="1587880">sides</span>
  <span m="1588510">are</span> <span m="1588630">equal</span> <span m="1588930">to</span>
  <span m="1589140">the</span> <span m="1589260">same</span> <span m="1589680">constant.</span></p><p><span
  m="1594970">So</span> <span m="1595080">now,</span> <span m="1596010">we</span>
  <span m="1596190">have</span> <span m="1596310">to</span> <span m="1596760">differential</span>
  <span m="1597390">equations.</span> <span m="1598710">We</span> <span m="1598860">have</span>
  <span m="1599400">1</span> <span m="1599640">over</span> <span m="1599820">x</span>
  <span m="1600810">second</span> <span m="1601170">derivative</span> <span m="1602070">with</span>
  <span m="1602250">respect</span> <span m="1602940">to</span> <span m="1603040">x</span>
  <span m="1603900">of</span> <span m="1604290">x</span> <span m="1605700">is</span>
  <span m="1605850">equal</span> <span m="1606120">to</span> <span m="1606270">a</span>
  <span m="1606360">concept.</span> <span m="1607570">And</span> <span m="1607590">we</span>
  <span m="1607740">have</span> <span m="1609740">1</span> <span m="1609990">over</span>
  <span m="1610170">v</span> <span m="1610410">squared</span> <span m="1611690">1</span>
  <span m="1612010">over</span> <span m="1612240">t</span> <span m="1613190">second</span>
  <span m="1613590">derivative</span> <span m="1614400">with</span> <span m="1614610">respect</span>
  <span m="1615060">to</span> <span m="1615180">t</span> <span m="1616270">of</span>
  <span m="1616440">T</span> <span m="1617130">is</span> <span m="1617280">equal</span>
  <span m="1617540">to</span> <span m="1617680">K.</span> <span m="1620160">So</span>
  <span m="1620640">now,</span> <span m="1620970">we're</span> <span m="1621420">on</span>
  <span m="1622170">firmer</span> <span m="1622650">ground.</span> <span m="1623290">We</span>
  <span m="1623370">know</span> <span m="1624030">about</span> <span m="1624360">solutions</span>
  <span m="1624900">to</span> <span m="1625020">this</span> <span m="1625230">kind</span>
  <span m="1625440">of</span> <span m="1625560">equation.</span></p><p><span m="1631200">And</span>
  <span m="1631270">so</span> <span m="1631420">there's</span> <span m="1631630">two</span>
  <span m="1632230">cases.</span> <span m="1633320">One</span> <span m="1633430">is</span>
  <span m="1633550">this</span> <span m="1633790">K</span> <span m="1634150">is</span>
  <span m="1634330">greater</span> <span m="1634720">than</span> <span m="1635320">0.</span>
  <span m="1635800">And</span> <span m="1635920">the</span> <span m="1636040">other</span>
  <span m="1636280">is</span> <span m="1636550">K</span> <span m="1637330">less</span>
  <span m="1637600">than</span> <span m="1637750">0.</span> <span m="1639440">So</span>
  <span m="1639560">let's</span> <span m="1639770">look</span> <span m="1639950">at</span>
  <span m="1640040">this</span> <span m="1640220">equation.</span> <span m="1641120">If</span>
  <span m="1641240">K</span> <span m="1641630">is</span> <span m="1641840">greater</span>
  <span m="1642290">than</span> <span m="1642470">0,</span> <span m="1643880">then</span>
  <span m="1644100">if</span> <span m="1644210">we</span> <span m="1644330">plug</span>
  <span m="1644720">in</span> <span m="1645980">a</span> <span m="1646070">sine</span>
  <span m="1646730">or a</span> <span m="1646910">cosine,</span> <span m="1648750">we</span>
  <span m="1648870">get</span> <span m="1649020">something</span> <span m="1649350">that's</span>
  <span m="1649620">less</span> <span m="1649950">than</span> <span m="1650070">0.</span>
  <span m="1651330">Because</span> <span m="1651690">the</span> <span m="1651780">derivative</span>
  <span m="1652380">of</span> <span m="1652560">sine</span> <span m="1653520">with</span>
  <span m="1653700">respect</span> <span m="1654390">to</span> <span m="1654600">its</span>
  <span m="1654810">variable</span> <span m="1655260">is</span> <span m="1655470">negative</span>
  <span m="1656580">cosine.</span> <span m="1657240">And</span> <span m="1657340">then</span>
  <span m="1657440">we</span> <span m="1657540">do it</span> <span m="1657630">again,</span>
  <span m="1658350">we</span> <span m="1658440">get</span> <span m="1658620">back</span>
  <span m="1659340">to</span> <span m="1659520">sine.</span> <span m="1660430">And</span>
  <span m="1660450">so</span> <span m="1661680">sines</span> <span m="1662040">and</span>
  <span m="1662130">cosines</span> <span m="1662640">are</span> <span m="1662730">no</span>
  <span m="1662880">good</span> <span m="1663840">for</span> <span m="1663960">this</span>
  <span m="1664200">equation</span> <span m="1664830">if</span> <span m="1665070">K</span>
  <span m="1665640">is</span> <span m="1665730">greater</span> <span m="1666060">than</span>
  <span m="1666210">0.</span></p><p><span m="1668090">But</span> <span m="1668300">exponentials--</span>
  <span m="1670280">so</span> <span m="1670940">we</span> <span m="1671030">can</span>
  <span m="1671210">have</span> <span m="1671420">e</span> <span m="1671720">to</span>
  <span m="1674420">some</span> <span m="1675140">constant</span> <span m="1676430">x</span>
  <span m="1677100">or</span> <span m="1677510">e</span> <span m="1677750">to</span>
  <span m="1677960">the</span> <span m="1678230">minus</span> <span m="1678800">some</span>
  <span m="1679110">constant</span> <span m="1679730">x.</span> <span m="1680730">Or</span>
  <span m="1680840">here,</span> <span m="1683540">for</span> <span m="1683930">the</span>
  <span m="1684230">negative</span> <span m="1685010">value</span> <span m="1685400">of</span>
  <span m="1685520">K,</span> <span m="1685980">we</span> <span m="1686060">could</span>
  <span m="1686240">have</span> <span m="1686810">sine</span> <span m="1687320">some</span>
  <span m="1687560">constant</span> <span m="1688610">x</span> <span m="1689690">and</span>
  <span m="1690470">cosine</span> <span m="1690970">of</span> <span m="1691020">some</span>
  <span m="1691520">constant</span> <span m="1691800">x.</span> <span m="1692600">We</span>
  <span m="1692720">know</span> <span m="1692960">that.</span> <span m="1695270">So</span>
  <span m="1695370">we</span> <span m="1695450">have</span> <span m="1695570">two</span>
  <span m="1695750">cases.</span> <span m="1699480">So</span> <span m="1700530">to</span>
  <span m="1700850">make</span> <span m="1701090">life</span> <span m="1701360">simple,</span>
  <span m="1702960">we</span> <span m="1703010">say</span> <span m="1703400">K</span>
  <span m="1704480">is</span> <span m="1704600">going</span> <span m="1704810">to</span>
  <span m="1704870">be</span> <span m="1705020">equal</span> <span m="1705320">to</span>
  <span m="1706190">lowercase</span> <span m="1706700">k</span> <span m="1706970">squared.</span>
  <span m="1710400">Because</span> <span m="1710700">we</span> <span m="1710820">want</span>
  <span m="1711000">to</span> <span m="1711060">use</span> <span m="1711330">this</span>
  <span m="1711510">lowercase</span> <span m="1712050">k</span> <span m="1712380">in</span>
  <span m="1712500">our</span> <span m="1712590">solutions.</span></p><p><span m="1715230">All</span>
  <span m="1715330">right.</span> <span m="1715980">So</span> <span m="1716460">I</span>
  <span m="1716670">may</span> <span m="1716850">have</span> <span m="1718440">confused</span>
  <span m="1719160">matters.</span> <span m="1719610">But</span> <span m="1720990">the</span>
  <span m="1721200">solution</span> <span m="1721800">for</span> <span m="1722130">the</span>
  <span m="1723600">time</span> <span m="1724830">equation</span> <span m="1726210">and</span>
  <span m="1726900">the</span> <span m="1727350">position</span> <span m="1727830">equation</span>
  <span m="1729030">are</span> <span m="1729660">clear.</span> <span m="1730680">And</span>
  <span m="1731310">so</span> <span m="1731670">depending</span> <span m="1732150">on</span>
  <span m="1732270">whether</span> <span m="1732600">K</span> <span m="1732900">is</span>
  <span m="1733020">positive</span> <span m="1733500">or</span> <span m="1733560">negative,</span>
  <span m="1733980">we're</span> <span m="1734130">dealing</span> <span m="1734490">with</span>
  <span m="1735560">sines</span> <span m="1735900">and</span> <span m="1735990">cosines</span>
  <span m="1737520">or</span> <span m="1738030">exponentials.</span> <span m="1740560">OK.</span>
  <span m="1741010">So</span> <span m="1741310">I</span> <span m="1741400">don't</span>
  <span m="1741550">want</span> <span m="1741730">to</span> <span m="1741790">belabor</span>
  <span m="1742300">this,</span> <span m="1743150">but</span> <span m="1743170">the</span>
  <span m="1743260">next</span> <span m="1743560">stage</span> <span m="1744760">is</span>
  <span m="1744940">boundary</span> <span m="1745360">conditions.</span></p><p><span
  m="1753220">We</span> <span m="1753370">don't</span> <span m="1753580">know</span>
  <span m="1754990">whether</span> <span m="1755410">K</span> <span m="1755680">positive</span>
  <span m="1756400">or</span> <span m="1756550">K</span> <span m="1756760">negative</span>
  <span m="1757270">is</span> <span m="1757390">possible.</span> <span m="1760350">But</span>
  <span m="1760400">we</span> <span m="1760520">do</span> <span m="1760700">know</span>
  <span m="1760940">boundary</span> <span m="1761360">conditions.</span> <span m="1762360">And</span>
  <span m="1762460">so</span> <span m="1762530">if</span> <span m="1762620">we</span>
  <span m="1762740">have</span> <span m="1762890">a</span> <span m="1762950">string</span>
  <span m="1764750">which</span> <span m="1764960">is</span> <span m="1765080">tied</span>
  <span m="1765410">down</span> <span m="1765680">at</span> <span m="1765800">the</span>
  <span m="1765980">end--</span> <span m="1766300">so</span> <span m="1766370">this</span>
  <span m="1766580">is</span> <span m="1767120">x</span> <span m="1767360">equals</span>
  <span m="1767660">0.</span> <span m="1768560">And</span> <span m="1768650">this</span>
  <span m="1768860">is</span> <span m="1769010">x</span> <span m="1769250">equals</span>
  <span m="1769550">L.</span> <span m="1772140">Then</span> <span m="1772350">we</span>
  <span m="1772590">input</span> <span m="1773030">impose</span> <span m="1773490">the</span>
  <span m="1773580">boundary</span> <span m="1773970">conditions.</span> <span m="1776016">Well,</span>
  <span m="1776580">the</span> <span m="1776670">boundary</span> <span m="1777030">conditions</span>
  <span m="1777720">are</span> <span m="1778320">u</span> <span m="1779090">of</span>
  <span m="1780240">0t</span> <span m="1782055">is</span> <span m="1782460">equal</span>
  <span m="1782760">to</span> <span m="1783030">0.</span> <span m="1783750">And</span>
  <span m="1783900">u</span> <span m="1784380">of</span> <span m="1784798">Lt</span>
  <span m="1786052">is</span> <span m="1786470">equal</span> <span m="1787110">to</span>
  <span m="1787200">0.</span></p><p><span m="1789960">So</span> <span m="1790170">if</span>
  <span m="1790260">we</span> <span m="1790380">take</span> <span m="1790890">the</span>
  <span m="1791400">K</span> <span m="1791860">greater</span> <span m="1792380">than</span>
  <span m="1792480">0</span> <span m="1792780">case,</span> <span m="1795470">u</span>
  <span m="1796196">of</span> <span m="1796930">0t</span> <span m="1799940">is</span>
  <span m="1800180">equal</span> <span m="1800510">to--</span> <span m="1811110">well,</span>
  <span m="1811560">let's</span> <span m="1811800">just</span> <span m="1811920">do</span>
  <span m="1812270">this</span> <span m="1812470">again.</span> <span m="1813390">0t.</span>
  <span m="1816120">We</span> <span m="1816480">have</span> <span m="1816795">x</span>
  <span m="1817110">of</span> <span m="1818480">0</span> <span m="1820150">times</span>
  <span m="1820790">T</span> <span m="1821590">of</span> <span m="1821790">t.</span>
  <span m="1822570">OK,</span> <span m="1823470">we</span> <span m="1823560">don't</span>
  <span m="1823710">really</span> <span m="1823950">care</span> <span m="1824220">about</span>
  <span m="1824460">this.</span> <span m="1825180">But</span> <span m="1825630">x</span>
  <span m="1825930">of</span> <span m="1826020">0</span> <span m="1828480">has</span>
  <span m="1828750">to</span> <span m="1828870">be</span> <span m="1829200">0--</span>
  <span m="1831830">I'm</span> <span m="1832310">sorry.</span> <span m="1832740">OK.</span>
  <span m="1833120">So</span> <span m="1834150">we</span> <span m="1834330">have</span>
  <span m="1834900">two</span> <span m="1835200">solutions.</span> <span m="1836310">If</span>
  <span m="1836460">K</span> <span m="1836700">is</span> <span m="1836820">greater</span>
  <span m="1837150">than</span> <span m="1837330">0,</span> <span m="1840370">we</span>
  <span m="1840550">have</span> <span m="1841330">the</span> <span m="1841480">exponential</span>
  <span m="1843640">terms.</span> <span m="1844030">So</span> <span m="1844240">we</span>
  <span m="1844390">have</span> <span m="1845080">Ae</span> <span m="1846290">to</span>
  <span m="1846400">the</span> <span m="1846710">0</span> <span m="1847810">plus</span>
  <span m="1848230">B</span> <span m="1849100">to</span> <span m="1849550">the</span>
  <span m="1850000">minus</span> <span m="1850450">0.</span> <span m="1854800">And</span>
  <span m="1854920">this</span> <span m="1855070">has</span> <span m="1855250">to</span>
  <span m="1855340">be</span> <span m="1855460">equal</span> <span m="1855700">to</span>
  <span m="1855790">0.</span> <span m="1859630">That's</span> <span m="1860396">x
  of 0.</span></p><p><span m="1864295">Well,</span> <span m="1864880">e</span> <span
  m="1865180">to the</span> <span m="1865360">0</span> <span m="1865750">is</span>
  <span m="1865990">1.</span> <span m="1866200">E to the</span> <span m="1866290">minus</span>
  <span m="1866590">0</span> <span m="1866890">is</span> <span m="1867040">1.</span>
  <span m="1867850">And</span> <span m="1868000">so</span> <span m="1868420">this</span>
  <span m="1868660">is</span> <span m="1868780">good.</span> <span m="1869590">A</span>
  <span m="1869860">has</span> <span m="1870130">to</span> <span m="1870220">be</span>
  <span m="1870310">equal</span> <span m="1870700">to</span> <span m="1870820">minus</span>
  <span m="1871240">B.</span> <span m="1875440">And</span> <span m="1875550">then</span>
  <span m="1875730">we</span> <span m="1875850">have</span> <span m="1876000">the</span>
  <span m="1876150">other</span> <span m="1876390">boundary</span> <span m="1876750">condition,</span>
  <span m="1877350">X</span> <span m="1877710">of</span> <span m="1878260">L.</span>
  <span m="1882060">We</span> <span m="1882210">have</span> <span m="1882795">A</span>
  <span m="1883260">e</span> <span m="1884400">to</span> <span m="1884550">the</span>
  <span m="1884730">L</span> <span m="1885162">plus</span> <span m="1886890">B</span>
  <span m="1887690">e</span> <span m="1888040">to the</span> <span m="1888390">minus</span>
  <span m="1888780">L.</span> <span m="1893660">Well,</span> <span m="1894380">I'm</span>
  <span m="1894530">sorry.</span> <span m="1895190">Let's</span> <span m="1895370">just</span>
  <span m="1895910">put</span> <span m="1896490">what</span> <span m="1896690">we</span>
  <span m="1896810">already</span> <span m="1897140">know.</span> <span m="1898290">Minus</span>
  <span m="1898740">A.</span> <span m="1900110">So</span> <span m="1900260">we</span>
  <span m="1900350">can</span> <span m="1900530">write</span> <span m="1900680">this</span>
  <span m="1900920">as</span> <span m="1901100">A</span> <span m="1901520">e to</span>
  <span m="1901990">the</span> <span m="1902540">L</span> <span m="1902930">minus</span>
  <span m="1903320">e</span> <span m="1903420">to</span> <span m="1903560">the</span>
  <span m="1903710">minus</span> <span m="1903960">L.</span> <span m="1904550">And</span>
  <span m="1905320">that</span> <span m="1905540">has</span> <span m="1905690">to</span>
  <span m="1905780">be</span> <span m="1905870">equal</span> <span m="1906050">to</span>
  <span m="1906140">0.</span> <span m="1907400">Can't</span> <span m="1907640">do</span>
  <span m="1907820">it.</span> <span m="1909530">This</span> <span m="1909710">can</span>
  <span m="1909860">never</span> <span m="1910130">be</span> <span m="1910250">0.</span></p><p><span
  m="1916580">So</span> <span m="1916930">that</span> <span m="1917140">means</span>
  <span m="1917890">the</span> <span m="1918010">K</span> <span m="1918310">greater</span>
  <span m="1918670">than</span> <span m="1918820">0</span> <span m="1919090">solutions</span>
  <span m="1919630">are</span> <span m="1919750">illegal.</span> <span m="1923950">Well,</span>
  <span m="1924340">that's</span> <span m="1925270">kind</span> <span m="1925480">of</span>
  <span m="1925540">bad</span> <span m="1925810">news.</span> <span m="1926170">Because</span>
  <span m="1926500">it</span> <span m="1926590">sounds</span> <span m="1926920">like</span>
  <span m="1927130">separation</span> <span m="1927730">of</span> <span m="1927790">variables</span>
  <span m="1928240">is</span> <span m="1928390">failing.</span> <span m="1929660">But</span>
  <span m="1929830">it</span> <span m="1929920">doesn't.</span> <span m="1930340">Because</span>
  <span m="1931050">the</span> <span m="1931180">K</span> <span m="1931630">less</span>
  <span m="1931960">than</span> <span m="1932080">0</span> <span m="1932350">solution</span>
  <span m="1932860">works.</span> <span m="1937060">So</span> <span m="1938320">for</span>
  <span m="1938500">K</span> <span m="1939100">less</span> <span m="1939430">than</span>
  <span m="1939580">0,</span> <span m="1940930">X</span> <span m="1941360">of</span>
  <span m="1941530">0</span> <span m="1942610">is</span> <span m="1942820">equal</span>
  <span m="1943150">to</span> <span m="1943780">C</span> <span m="1944470">sine</span>
  <span m="1945530">0</span> <span m="1946450">plus</span> <span m="1947050">D</span>
  <span m="1947710">cosine</span> <span m="1948980">0.</span> <span m="1951070">And</span>
  <span m="1951490">so</span> <span m="1951730">that</span> <span m="1951970">means</span>
  <span m="1952240">D</span> <span m="1952520">is</span> <span m="1952600">equal</span>
  <span m="1952740">to</span> <span m="1952960">0.</span> <span m="1954790">Things</span>
  <span m="1955030">are</span> <span m="1955090">dying.</span> <span m="1956710">And</span>
  <span m="1957070">X</span> <span m="1957840">of</span> <span m="1958130">L,</span>
  <span m="1959230">boundary condition,</span> <span m="1960460">is</span> <span m="1961210">C</span>
  <span m="1962530">sine</span> <span m="1970320">KL</span> <span m="1973640">is</span>
  <span m="1973940">equal</span> <span m="1974330">to</span> <span m="1974480">0.</span></p><p><span
  m="1976200">And</span> <span m="1976390">this</span> <span m="1976600">we</span>
  <span m="1976720">can</span> <span m="1976870">solve.</span> <span m="1979000">So</span>
  <span m="1979690">sine</span> <span m="1980140">is</span> <span m="1980350">equal</span>
  <span m="1980590">to</span> <span m="1980680">0</span> <span m="1981160">when</span>
  <span m="1981490">KL</span> <span m="1982060">is</span> <span m="1982240">equal</span>
  <span m="1982510">to</span> <span m="1982720">0,</span> <span m="1990790">0</span>
  <span m="1991130">pi,</span> <span m="1991760">2</span> <span m="1992180">pi,</span>
  <span m="1992430">et</span> <span m="1992690">cetera.</span> <span m="1993160">And</span>
  <span m="1993290">so</span> <span m="1993470">we</span> <span m="1993620">have</span>
  <span m="1994280">KL</span> <span m="1995900">is</span> <span m="1996080">equal</span>
  <span m="1996410">to</span> <span m="1996770">n</span> <span m="1997450">pi.</span>
  <span m="2002250">So</span> <span m="2002460">we</span> <span m="2002610">can</span>
  <span m="2002790">write</span> <span m="2003060">this</span> <span m="2003825">as</span>
  <span m="2004230">Kn</span> <span m="2005070">is</span> <span m="2005250">equal</span>
  <span m="2005490">to</span> <span m="2005590">n</span> <span m="2006180">pi</span>
  <span m="2006820">over</span> <span m="2007520">L.</span> <span m="2009240">We</span>
  <span m="2009330">get</span> <span m="2009480">quantization.</span> <span m="2010320">This</span>
  <span m="2010530">isn't</span> <span m="2010770">quantum</span> <span m="2011010">mechanics.</span>
  <span m="2012990">But</span> <span m="2013170">there</span> <span m="2013380">are</span>
  <span m="2013470">certain</span> <span m="2013830">allowed</span> <span m="2014280">values</span>
  <span m="2014790">of</span> <span m="2014940">this</span> <span m="2015540">K</span>
  <span m="2016440">constant.</span> <span m="2018670">And</span> <span m="2019660">we</span>
  <span m="2019990">have</span> <span m="2020110">a</span> <span m="2020170">bunch</span>
  <span m="2020380">of</span> <span m="2020440">solutions.</span></p><p><span m="2023940">And</span>
  <span m="2024040">so</span> <span m="2024130">what</span> <span m="2024250">do</span>
  <span m="2024310">they</span> <span m="2024460">look</span> <span m="2024670">like?</span>
  <span m="2025450">So</span> <span m="2027250">n</span> <span m="2027370">equals</span>
  <span m="2027670">0,</span> <span m="2030550">n</span> <span m="2030730">equals</span>
  <span m="2031060">1,</span> <span m="2034030">n</span> <span m="2034150">equals</span>
  <span m="2034480">2.</span> <span m="2035920">So</span> <span m="2036070">what</span>
  <span m="2036240">does</span> <span m="2036370">the</span> <span m="2036460">0</span>
  <span m="2036790">solution</span> <span m="2037510">look</span> <span m="2037720">like?</span>
  <span m="2044930">Yes?</span></p><p><span m="2045848">AUDIENCE:</span> <span m="2046087">No</span>
  <span m="2046326">node.</span></p><p><span m="2047760">ROBERT FIELD:</span> <span
  m="2047930">Nothing.</span> <span m="2051380">So</span> <span m="2051600">we</span>
  <span m="2051750">don't</span> <span m="2051960">even</span> <span m="2052199">think</span>
  <span m="2052469">about</span> <span m="2052770">this.</span> <span m="2053070">We</span>
  <span m="2053250">say,</span> <span m="2053580">n</span> <span m="2053730">equals</span>
  <span m="2053969">0</span> <span m="2054239">is</span> <span m="2054360">not</span>
  <span m="2054540">a</span> <span m="2054600">solution.</span> <span m="2055650">Because</span>
  <span m="2056580">the</span> <span m="2057270">wave</span> <span m="2057570">isn't</span>
  <span m="2057750">there.</span> <span m="2059909">No</span> <span m="2060090">nodes,</span>
  <span m="2062500">one</span> <span m="2062739">node.</span> <span m="2064760">And</span>
  <span m="2064820">if</span> <span m="2064909">we</span> <span m="2065000">look</span>
  <span m="2065179">at</span> <span m="2065270">this</span> <span m="2065449">carefully,</span>
  <span m="2067320">the</span> <span m="2067440">node</span> <span m="2067770">is</span>
  <span m="2067949">always</span> <span m="2068429">at</span> <span m="2068580">a</span>
  <span m="2068639">cemetery</span> <span m="2069090">point.</span> <span m="2070139">It's</span>
  <span m="2070290">in</span> <span m="2070409">the</span> <span m="2070500">middle.</span>
  <span m="2071699">If</span> <span m="2071850">we</span> <span m="2072000">have</span>
  <span m="2072449">the</span> <span m="2072570">next</span> <span m="2072900">one,</span>
  <span m="2073440">we'll</span> <span m="2073620">have</span> <span m="2073860">two</span>
  <span m="2074130">nodes.</span> <span m="2075270">And</span> <span m="2075389">they'll</span>
  <span m="2075630">be</span> <span m="2075870">at</span> <span m="2075989">the</span>
  <span m="2076179">1/3</span> <span m="2076800">2/3</span> <span m="2077070">point.</span>
  <span m="2078360">And</span> <span m="2078719">so</span> <span m="2078929">we</span>
  <span m="2079080">know</span> <span m="2080280">where</span> <span m="2080460">the</span>
  <span m="2080550">nodes</span> <span m="2080880">are.</span></p><p><span m="2081960">We</span>
  <span m="2082139">also</span> <span m="2082560">know</span> <span m="2083489">that</span>
  <span m="2083639">the</span> <span m="2083790">amplitude</span> <span m="2084360">of</span>
  <span m="2084480">each</span> <span m="2084690">loop</span> <span m="2085080">of</span>
  <span m="2085199">the</span> <span m="2085290">wave</span> <span m="2085469">function</span>
  <span m="2085889">is</span> <span m="2086010">the</span> <span m="2086100">same.</span>
  <span m="2086460">But</span> <span m="2086639">it</span> <span m="2086760">alternates</span>
  <span m="2087280">in</span> <span m="2087739">sine.</span> <span m="2090199">So</span>
  <span m="2090800">you</span> <span m="2090949">can</span> <span m="2091130">draw</span>
  <span m="2091370">cartoons</span> <span m="2091880">now</span> <span m="2092929">at</span>
  <span m="2093080">will.</span> <span m="2093500">Because</span> <span m="2094699">this</span>
  <span m="2095150">spatial</span> <span m="2095659">part</span> <span m="2096170">of</span>
  <span m="2097460">the</span> <span m="2097790">solution</span> <span m="2098330">to</span>
  <span m="2098450">this</span> <span m="2098690">wave</span> <span m="2099350">is</span>
  <span m="2099560">clear.</span> <span m="2100610">Any</span> <span m="2101060">value</span>
  <span m="2101540">of</span> <span m="2101720">the</span> <span m="2101840">quantum</span>
  <span m="2102230">number,</span> <span m="2102810">or</span> <span m="2102890">the</span>
  <span m="2103140">n,</span> <span m="2104060">gives</span> <span m="2104360">you</span>
  <span m="2104600">a</span> <span m="2104690">picture</span> <span m="2105110">that</span>
  <span m="2105230">you</span> <span m="2105350">can</span> <span m="2105530">draw</span>
  <span m="2105830">in</span> <span m="2105980">seconds.</span> <span m="2108690">And</span>
  <span m="2108710">there</span> <span m="2108800">are</span> <span m="2108830">a</span>
  <span m="2108860">lot</span> <span m="2109100">of</span> <span m="2109370">quantum</span>
  <span m="2109640">mechanical</span> <span m="2110090">problems</span> <span m="2110570">like</span>
  <span m="2110960">that.</span></p><p><span m="2113540">But</span> <span m="2113560">sometimes,</span>
  <span m="2114850">you</span> <span m="2115030">have</span> <span m="2115210">to</span>
  <span m="2115300">keep</span> <span m="2115540">in</span> <span m="2115660">mind</span>
  <span m="2116590">that</span> <span m="2117190">the</span> <span m="2117640">node</span>
  <span m="2118240">separation,</span> <span m="2119140">in</span> <span m="2119290">other</span>
  <span m="2119500">words--</span> <span m="2123390">well,</span> <span m="2123550">let's</span>
  <span m="2123730">just</span> <span m="2123880">say</span> <span m="2124480">node</span>
  <span m="2124870">separation</span> <span m="2128170">is</span> <span m="2128530">lambda</span>
  <span m="2128860">over</span> <span m="2129100">2.</span> <span m="2131580">And</span>
  <span m="2131830">lambda</span> <span m="2132190">over</span> <span m="2132460">2</span>
  <span m="2134350">is</span> <span m="2134800">equal</span> <span m="2135220">to</span>
  <span m="2136810">1/2</span> <span m="2138320">h</span> <span m="2138840">over</span>
  <span m="2139080">p.</span> <span m="2141820">So</span> <span m="2142150">if</span>
  <span m="2142300">we</span> <span m="2142450">know</span> <span m="2142900">what</span>
  <span m="2143170">the</span> <span m="2144250">momentum</span> <span m="2144910">is,</span>
  <span m="2146790">or</span> <span m="2147100">we</span> <span m="2147310">know</span>
  <span m="2147520">what</span> <span m="2147670">the</span> <span m="2147790">kinetic</span>
  <span m="2148300">energy</span> <span m="2148720">is,</span> <span m="2148960">we</span>
  <span m="2149140">know</span> <span m="2149320">what</span> <span m="2149500">the</span>
  <span m="2149650">momentum</span> <span m="2150150">is.</span> <span m="2150430">We</span>
  <span m="2150580">know</span> <span m="2150960">how</span> <span m="2152170">momentum</span>
  <span m="2152890">is</span> <span m="2153070">encoded</span> <span m="2153610">in</span>
  <span m="2153760">node</span> <span m="2154000">separations.</span></p><p><span
  m="2157470">So</span> <span m="2157650">everything</span> <span m="2158190">we</span>
  <span m="2158280">want</span> <span m="2158490">to</span> <span m="2158550">know</span>
  <span m="2158790">about</span> <span m="2159060">a</span> <span m="2159300">one-dimensional</span>
  <span m="2159810">problem</span> <span m="2160590">is</span> <span m="2160800">expressed</span>
  <span m="2161850">in</span> <span m="2162600">the</span> <span m="2163680">spacing</span>
  <span m="2164280">of</span> <span m="2164400">nodes</span> <span m="2165510">and</span>
  <span m="2165660">the</span> <span m="2165810">amplitude</span> <span m="2166380">between</span>
  <span m="2166830">nodes.</span> <span m="2168060">And</span> <span m="2168180">the</span>
  <span m="2168330">amplitude</span> <span m="2168900">between</span> <span m="2169290">nodes</span>
  <span m="2169650">have</span> <span m="2169800">something</span> <span m="2170070">to</span>
  <span m="2170130">do</span> <span m="2170340">with</span> <span m="2170550">the</span>
  <span m="2171990">momentum,</span> <span m="2172420">too.</span> <span m="2173340">Because</span>
  <span m="2173670">if</span> <span m="2173760">you're</span> <span m="2173850">going</span>
  <span m="2174090">from</span> <span m="2174270">here</span> <span m="2174450">to</span>
  <span m="2174570">here</span> <span m="2174840">at</span> <span m="2174960">some</span>
  <span m="2178770">high</span> <span m="2179100">velocity,</span> <span m="2179980">there's</span>
  <span m="2180060">not</span> <span m="2180240">much</span> <span m="2180480">amplitude.</span>
  <span m="2182150">And</span> <span m="2182620">at</span> <span m="2183010">a</span>
  <span m="2183060">lower</span> <span m="2183420">velocity,</span> <span m="2184500">you</span>
  <span m="2184620">get</span> <span m="2184800">more</span> <span m="2185100">amplitude.</span>
  <span m="2186690">And</span> <span m="2186840">so</span> <span m="2187170">the</span>
  <span m="2188790">amplitude</span> <span m="2189660">in</span> <span m="2189840">each</span>
  <span m="2190110">of</span> <span m="2190230">these</span> <span m="2190950">node</span>
  <span m="2191250">to</span> <span m="2191400">node</span> <span m="2191730">separate</span>
  <span m="2192150">sections</span> <span m="2193050">is</span> <span m="2193260">related</span>
  <span m="2193800">to</span> <span m="2193950">the</span> <span m="2194130">average</span>
  <span m="2194760">momentum</span> <span m="2195750">of</span> <span m="2195900">the</span>
  <span m="2195990">classical</span> <span m="2196590">particle</span> <span m="2197280">in</span>
  <span m="2197460">that</span> <span m="2197910">section.</span></p><p><span m="2200070">So</span>
  <span m="2200270">the</span> <span m="2200390">classical</span> <span m="2200705">mechanics</span>
  <span m="2201020">is</span> <span m="2201440">going</span> <span m="2201860">to</span>
  <span m="2202280">be</span> <span m="2203360">extremely</span> <span m="2204170">important</span>
  <span m="2205210">in</span> <span m="2205340">drawing</span> <span m="2205700">cartoons</span>
  <span m="2206510">for</span> <span m="2206750">quantum</span> <span m="2207110">mechanical</span>
  <span m="2207650">systems.</span> <span m="2209180">Not</span> <span m="2209390">in</span>
  <span m="2209450">the</span> <span m="2209540">textbooks.</span> <span m="2213550">We</span>
  <span m="2213700">supposedly</span> <span m="2214390">know</span> <span m="2214660">classical</span>
  <span m="2215110">mechanics</span> <span m="2215500">pretty</span> <span m="2215740">well,</span>
  <span m="2216400">and</span> <span m="2216520">especially</span> <span m="2217090">here</span>
  <span m="2217250">at</span> <span m="2217380">MIT.</span> <span m="2219160">So</span>
  <span m="2219340">you</span> <span m="2219460">might</span> <span m="2219580">as</span>
  <span m="2219670">well</span> <span m="2219790">use</span> <span m="2220120">that</span>
  <span m="2220750">in</span> <span m="2220930">order</span> <span m="2221140">to</span>
  <span m="2221410">get</span> <span m="2221860">an</span> <span m="2221980">idea</span>
  <span m="2222400">of</span> <span m="2222550">how</span> <span m="2223300">all</span>
  <span m="2223570">of</span> <span m="2223690">the</span> <span m="2224620">quantum</span>
  <span m="2224980">mechanical</span> <span m="2225460">problems</span> <span m="2226240">you're</span>
  <span m="2226420">facing</span> <span m="2226900">will</span> <span m="2227080">be</span>
  <span m="2227530">behaving.</span></p><p><span m="2229790">OK.</span> <span m="2230870">So</span>
  <span m="2232250">the</span> <span m="2232340">next</span> <span m="2232640">thing</span>
  <span m="2233690">we</span> <span m="2233810">want</span> <span m="2233990">to</span>
  <span m="2234080">do</span> <span m="2235700">is</span> <span m="2235910">finish</span>
  <span m="2236300">the</span> <span m="2236450">job.</span> <span m="2238220">And</span>
  <span m="2238670">so</span> <span m="2239240">I</span> <span m="2239390">can</span>
  <span m="2239570">simply</span> <span m="2239960">write</span> <span m="2240230">down</span>
  <span m="2241070">the</span> <span m="2241490">time-dependent</span> <span m="2242030">solutions.</span>
  <span m="2243110">They</span> <span m="2243290">are</span> <span m="2243500">E</span>
  <span m="2244370">sine</span> <span m="2246710">vkn</span> <span m="2246980">t</span>
  <span m="2249060">plus</span> <span m="2250780">F</span> <span m="2253800">cosine</span>
  <span m="2259070">vkn</span> <span m="2260025">t.</span> <span m="2264840">And</span>
  <span m="2265050">we</span> <span m="2265170">can</span> <span m="2265350">say</span>
  <span m="2266280">that--</span> <span m="2267120">rather</span> <span m="2267480">than</span>
  <span m="2267630">carrying</span> <span m="2267990">around</span> <span m="2268320">all</span>
  <span m="2268500">this</span> <span m="2268650">stuff,</span> <span m="2269760">we</span>
  <span m="2269910">can</span> <span m="2270120">say</span> <span m="2270660">omega</span>
  <span m="2271340">n</span> <span m="2272730">is</span> <span m="2273330">vkn.</span>
  <span m="2280540">Isn't</span> <span m="2280700">that</span> <span m="2280880">nice?</span>
  <span m="2283050">So</span> <span m="2283260">we</span> <span m="2283410">have</span>
  <span m="2283800">a</span> <span m="2283890">frequency</span> <span m="2285770">for</span>
  <span m="2285920">the</span> <span m="2286310">time-dependent</span> <span m="2286700">part,</span>
  <span m="2287360">which</span> <span m="2287570">is an integer multiple</span> <span
  m="2288800">of</span> <span m="2288950">this</span> <span m="2289250">constant</span>
  <span m="2289730">V</span> <span m="2290540">times</span> <span m="2290990">this</span>
  <span m="2291950">[? vector. ?]</span> <span m="2292910">Or</span> <span m="2293060">this</span>
  <span m="2293420">you</span> <span m="2293630">can</span> <span m="2293810">think</span>
  <span m="2294020">of</span> <span m="2294180">as</span> <span m="2294510">just</span>
  <span m="2294740">k</span> <span m="2294995">sub</span> <span m="2295250">n.</span></p><p><span
  m="2297570">So</span> <span m="2297760">we</span> <span m="2297870">can</span> <span
  m="2298050">rewrite</span> <span m="2298440">this</span> <span m="2299490">in</span>
  <span m="2299980">a</span> <span m="2300090">frequency</span> <span m="2300720">and</span>
  <span m="2301260">phase</span> <span m="2301730">form.</span> <span m="2302250">We</span>
  <span m="2302400">have</span> <span m="2303210">now</span> <span m="2303450">the</span>
  <span m="2303570">full</span> <span m="2303840">solution.</span> <span m="2306000">We</span>
  <span m="2306150">have</span> <span m="2306780">A n</span> <span m="2308610">sine</span>
  <span m="2309530">n pi L</span> <span m="2309940">over</span> <span m="2310350">x.</span>
  <span m="2315210">And</span> <span m="2315360">then</span> <span m="2316500">this</span>
  <span m="2317790">e</span> <span m="2318210">N</span> <span m="2320250">sine</span>
  <span m="2326320">n</span> <span m="2326575">pi--</span> <span m="2336322">I'm</span>
  <span m="2336800">so</span> <span m="2337010">used</span> <span m="2337190">to</span>
  <span m="2337280">the</span> <span m="2337400">pictures</span> <span m="2337880">I</span>
  <span m="2337970">don't</span> <span m="2338140">even</span> <span m="2338350">want</span>
  <span m="2338510">to</span> <span m="2338570">look</span> <span m="2338750">at</span>
  <span m="2338840">the</span> <span m="2338960">equations</span> <span m="2339440">anymore--</span>
  <span m="2341393">n</span> <span m="2342360">omega</span> <span m="2342820">t</span>
  <span m="2344130">plus</span> <span m="2345010">F</span> <span m="2345450">n</span>
  <span m="2346610">cosine</span> <span m="2348650">n</span> <span m="2349050">omega</span>
  <span m="2349470">t.</span> <span m="2351290">OK.</span></p><p><span m="2360590">So</span>
  <span m="2360800">we</span> <span m="2360950">can</span> <span m="2361100">also</span>
  <span m="2361490">take</span> <span m="2361790">this</span> <span m="2362870">and</span>
  <span m="2363020">rewrite</span> <span m="2363470">it</span> <span m="2363980">in</span>
  <span m="2364130">a</span> <span m="2364190">simpler</span> <span m="2364580">form,</span>
  <span m="2365440">E</span> <span m="2366680">n</span> <span m="2367010">prime</span>
  <span m="2367880">cosine</span> <span m="2370430">n</span> <span m="2371120">omega</span>
  <span m="2371840">t</span> <span m="2373700">plus</span> <span m="2374530">phi n.</span>
  <span m="2376160">So</span> <span m="2376400">we</span> <span m="2376550">can</span>
  <span m="2376730">combine</span> <span m="2377180">these</span> <span m="2377420">two</span>
  <span m="2377600">terms</span> <span m="2378440">as</span> <span m="2378620">a</span>
  <span m="2378680">single</span> <span m="2379160">cosine</span> <span m="2379700">with</span>
  <span m="2379850">a</span> <span m="2379910">phase</span> <span m="2380210">vector.</span>
  <span m="2386500">OK.</span> <span m="2387360">So</span> <span m="2387470">now,</span>
  <span m="2387740">we're</span> <span m="2387860">ready</span> <span m="2388610">to</span>
  <span m="2388730">actually</span> <span m="2390350">go</span> <span m="2390680">to</span>
  <span m="2390830">the</span> <span m="2392300">specific</span> <span m="2393530">thing</span>
  <span m="2393860">that</span> <span m="2394010">you</span> <span m="2394130">do</span>
  <span m="2396410">in</span> <span m="2396530">a</span> <span m="2396590">real</span>
  <span m="2397640">experiment</span> <span m="2398330">or</span> <span m="2398500">a</span>
  <span m="2398540">real</span> <span m="2398930">musical</span> <span m="2399185">instrument.</span></p><p><span
  m="2402870">We</span> <span m="2402990">say,</span> <span m="2403290">OK,</span>
  <span m="2403730">here</span> <span m="2404020">is</span> <span m="2404580">the</span>
  <span m="2404910">actual</span> <span m="2405900">initial</span> <span m="2406290">condition,</span>
  <span m="2407400">the</span> <span m="2407520">pluck</span> <span m="2407910">of</span>
  <span m="2408090">the</span> <span m="2408210">system.</span> <span m="2410880">And</span>
  <span m="2413766">the</span> <span m="2414150">pluck</span> <span m="2414480">usually</span>
  <span m="2414840">occurs</span> <span m="2415200">at</span> <span m="2415370">t
  equals</span> <span m="2415640">0.</span> <span m="2415950">But</span> <span m="2416100">I'll</span>
  <span m="2416220">just</span> <span m="2416880">specify</span> <span m="2418140">it</span>
  <span m="2418440">here.</span> <span m="2419440">And</span> <span m="2419880">what</span>
  <span m="2420030">we</span> <span m="2420180">have</span> <span m="2420990">is</span>
  <span m="2421170">now</span> <span m="2421980">a</span> <span m="2422490">sum</span>
  <span m="2424170">over</span> <span m="2425390">as</span> <span m="2425550">many</span>
  <span m="2425940">normal</span> <span m="2426300">modes</span> <span m="2426630">as</span>
  <span m="2426780">you</span> <span m="2426870">want.</span> <span m="2427800">We</span>
  <span m="2427980">have</span> <span m="2428280">A n</span> <span m="2430520">E</span>
  <span m="2430860">n</span> <span m="2431970">prime</span> <span m="2433680">times</span>
  <span m="2433980">sine</span> <span m="2439110">n</span> <span m="2439290">pi</span>
  <span m="2440230">over</span> <span m="2440490">L x</span> <span m="2441930">times</span>
  <span m="2442350">cosine</span> <span m="2445030">N</span> <span m="2446030">omega</span>
  <span m="2446980">t</span> <span m="2448210">plus</span> <span m="2449030">phi</span>
  <span m="2449530">N.</span></p><p><span m="2451600">So</span> <span m="2451810">we</span>
  <span m="2451990">have</span> <span m="2452510">a</span> <span m="2452770">bunch</span>
  <span m="2453190">of</span> <span m="2453370">terms</span> <span m="2453730">like</span>
  <span m="2453970">this,</span> <span m="2454670">a</span> <span m="2454780">spacial</span>
  <span m="2455290">factor,</span> <span m="2456160">and</span> <span m="2456240">a</span>
  <span m="2456310">temporal</span> <span m="2456700">factor.</span> <span m="2458430">And</span>
  <span m="2458630">you</span> <span m="2458730">can</span> <span m="2458880">draw</span>
  <span m="2459060">pictures</span> <span m="2459480">of</span> <span m="2459540">both.</span>
  <span m="2462590">Now,</span> <span m="2462860">but</span> <span m="2463010">there</span>
  <span m="2463150">is</span> <span m="2463280">another</span> <span m="2463620">simplification.</span>
  <span m="2465000">From</span> <span m="2465200">trigonometry,</span> <span m="2466980">sine</span>
  <span m="2467750">A</span> <span m="2469920">cosine</span> <span m="2471810">B--</span>
  <span m="2472260">we</span> <span m="2472440">have</span> <span m="2472560">sine</span>
  <span m="2472950">and</span> <span m="2473070">cosine--</span> <span m="2475020">can</span>
  <span m="2475200">be</span> <span m="2475320">written</span> <span m="2475770">as</span>
  <span m="2476190">1/2</span> <span m="2477240">times</span> <span m="2479030">sine</span>
  <span m="2482860">n pi L x</span> <span m="2488040">plus</span> <span m="2488730">n</span>
  <span m="2489150">omega</span> <span m="2489940">t</span> <span m="2492432">plus</span>
  <span m="2492930">phi n</span> <span m="2494430">plus</span> <span m="2499860">sine</span>
  <span m="2503510">n pi L x</span> <span m="2506810">minus</span> <span m="2507080">n</span>
  <span m="2507350">omega</span> <span m="2508580">t</span> <span m="2509180">minus</span>
  <span m="2509600">phi</span> <span m="2509990">n.</span></p><p><span m="2511250">So</span>
  <span m="2511460">these</span> <span m="2511700">are</span> <span m="2511880">the</span>
  <span m="2512030">two</span> <span m="2513620">possible</span> <span m="2514340">solutions.</span>
  <span m="2515450">And</span> <span m="2515600">we</span> <span m="2515720">can</span>
  <span m="2515900">write</span> <span m="2516140">them</span> <span m="2516320">now</span>
  <span m="2516710">in</span> <span m="2516860">terms</span> <span m="2517160">of</span>
  <span m="2517220">position</span> <span m="2517730">factor</span> <span m="2518690">at</span>
  <span m="2519050">a</span> <span m="2519140">time</span> <span m="2519470">factor</span>
  <span m="2520550">in</span> <span m="2520730">the</span> <span m="2520880">same</span>
  <span m="2523290">sine</span> <span m="2524100">or</span> <span m="2524250">cosine</span>
  <span m="2524505">function.</span> <span m="2527290">So</span> <span m="2527410">these</span>
  <span m="2527650">are</span> <span m="2527740">the</span> <span m="2527830">things.</span>
  <span m="2528550">Now,</span> <span m="2528790">we're</span> <span m="2528910">ready</span>
  <span m="2529180">to</span> <span m="2529300">make</span> <span m="2529570">a</span>
  <span m="2529630">picture.</span></p><p><span m="2532610">OK.</span> <span m="2533530">So</span>
  <span m="2533770">these</span> <span m="2534070">are</span> <span m="2534490">the</span>
  <span m="2534730">actual</span> <span m="2535270">things</span> <span m="2535750">that</span>
  <span m="2535870">you</span> <span m="2536050">make</span> <span m="2536830">by</span>
  <span m="2537340">exciting</span> <span m="2538340">the</span> <span m="2538430">system</span>
  <span m="2539020">not</span> <span m="2539380">in</span> <span m="2539500">an</span>
  <span m="2539650">eigenfunction.</span> <span m="2542010">But</span> <span m="2542150">it's</span>
  <span m="2542300">a</span> <span m="2542370">superposition</span> <span m="2543120">of</span>
  <span m="2543240">eigenfunctions.</span> <span m="2547250">And</span> <span m="2547600">again,</span>
  <span m="2548140">there</span> <span m="2548350">are</span> <span m="2548470">certain</span>
  <span m="2548800">things</span> <span m="2549130">you</span> <span m="2549280">learn.</span>
  <span m="2553030">If</span> <span m="2554170">you</span> <span m="2554320">have</span>
  <span m="2554560">a</span> <span m="2554620">pure</span> <span m="2555340">eigenfunction,</span>
  <span m="2557570">you</span> <span m="2557690">have</span> <span m="2557810">standing</span>
  <span m="2558170">waves.</span> <span m="2559560">There's</span> <span m="2559740">no</span>
  <span m="2560310">left-right</span> <span m="2560520">motion.</span> <span m="2561360">There's</span>
  <span m="2561540">no</span> <span m="2561720">breathing</span> <span m="2562200">motion.</span>
  <span m="2562650">There's</span> <span m="2562890">only</span> <span m="2563410">up-down</span>
  <span m="2563910">motion</span> <span m="2564690">of</span> <span m="2564840">each</span>
  <span m="2565110">loop</span> <span m="2565590">of</span> <span m="2565740">the</span>
  <span m="2565860">wave</span> <span m="2566040">function.</span></p><p><span m="2568760">If</span>
  <span m="2568810">you</span> <span m="2568870">have</span> <span m="2569020">a</span>
  <span m="2569080">superposition</span> <span m="2569890">of</span> <span m="2570040">two</span>
  <span m="2571090">or</span> <span m="2571240">more</span> <span m="2571990">functions,</span>
  <span m="2573550">which</span> <span m="2574360">are</span> <span m="2575350">all</span>
  <span m="2576025">of</span> <span m="2576280">even</span> <span m="2576850">n,</span>
  <span m="2579860">then</span> <span m="2580220">what</span> <span m="2580400">happens</span>
  <span m="2580880">is</span> <span m="2581180">you</span> <span m="2581300">have</span>
  <span m="2581480">no</span> <span m="2582200">motions,</span> <span m="2582950">you</span>
  <span m="2583100">just</span> <span m="2583340">have</span> <span m="2583490">breathing.</span>
  <span m="2584450">In</span> <span m="2584600">other</span> <span m="2584780">words,</span>
  <span m="2585210">you</span> <span m="2585230">have</span> <span m="2585410">a</span>
  <span m="2585440">function</span> <span m="2586220">that</span> <span m="2586340">might</span>
  <span m="2586580">look</span> <span m="2586790">sort</span> <span m="2587030">of</span>
  <span m="2587120">like</span> <span m="2587300">this</span> <span m="2587600">at</span>
  <span m="2587690">one</span> <span m="2587900">time</span> <span m="2588910">and</span>
  <span m="2589190">like</span> <span m="2589460">that</span> <span m="2589900">at</span>
  <span m="2590040">another</span> <span m="2590390">time.</span> <span m="2592570">So</span>
  <span m="2592740">amplitude</span> <span m="2593270">is</span> <span m="2593400">moving.</span>
  <span m="2594750">So</span> <span m="2595930">it</span> <span m="2596670">can</span>
  <span m="2596880">be</span> <span m="2597000">moving.</span> <span m="2598740">And</span>
  <span m="2598930">in between,</span> <span m="2599400">it's</span> <span m="2599490">sort</span>
  <span m="2599640">of</span> <span m="2599730">like</span> <span m="2599910">this.</span></p><p><span
  m="2602530">Now,</span> <span m="2602670">if</span> <span m="2602820">you</span>
  <span m="2602940">have</span> <span m="2603510">a</span> <span m="2603630">function</span>
  <span m="2604230">which</span> <span m="2604500">involves</span> <span m="2604950">both</span>
  <span m="2605370">even</span> <span m="2606030">and</span> <span m="2606360">odd</span>
  <span m="2606810">n,</span> <span m="2608300">you</span> <span m="2608420">have</span>
  <span m="2608570">left-right</span> <span m="2609020">motion.</span> <span m="2612030">This</span>
  <span m="2612210">is</span> <span m="2612360">true</span> <span m="2612540">in</span>
  <span m="2612630">quantum</span> <span m="2612870">mechanics,</span> <span m="2613290">too.</span>
  <span m="2614400">So</span> <span m="2614730">you</span> <span m="2614910">only</span>
  <span m="2615210">get</span> <span m="2615990">motion</span> <span m="2617040">if</span>
  <span m="2617190">you're</span> <span m="2617520">making</span> <span m="2618240">superposition</span>
  <span m="2619050">of</span> <span m="2619290">eigen--</span> <span m="2620040">Yes?</span></p><p><span
  m="2620610">AUDIENCE:</span> <span m="2620665">What</span> <span m="2620720">is</span>
  <span m="2620850">the</span> <span m="2620910">difference</span> <span m="2621210">between</span>
  <span m="2621570">breathing</span> <span m="2622350">and</span> <span m="2622920">the</span>
  <span m="2623400">standing</span> <span m="2623880">wave</span> <span m="2624230">with</span>
  <span m="2624450">no</span> <span m="2624630">nodes?</span></p><p><span m="2626580">ROBERT
  FIELD:</span> <span m="2626700">Well,</span> <span m="2626820">for</span> <span
  m="2627000">this</span> <span m="2627240">picture,</span> <span m="2629220">this</span>
  <span m="2629430">is</span> <span m="2629550">over-simple.</span> <span m="2630930">So</span>
  <span m="2631530">I</span> <span m="2631560">mean,</span> <span m="2631710">you</span>
  <span m="2632490">could</span> <span m="2632700">have--</span> <span m="2636360">basically,</span>
  <span m="2636930">what's</span> <span m="2637140">happening</span> <span m="2637650">is</span>
  <span m="2637920">amplitude</span> <span m="2638400">is</span> <span m="2638520">moving</span>
  <span m="2638880">from</span> <span m="2639120">middle</span> <span m="2639390">to</span>
  <span m="2639480">the</span> <span m="2639660">edges</span> <span m="2639960">and</span>
  <span m="2640050">back.</span> <span m="2641340">And</span> <span m="2642030">so</span>
  <span m="2643590">yes.</span> <span m="2645430">But</span> <span m="2646030">you</span>
  <span m="2646180">want</span> <span m="2646390">to</span> <span m="2646450">develop</span>
  <span m="2646930">your</span> <span m="2647080">own</span> <span m="2647890">language,</span>
  <span m="2648530">your</span> <span m="2648580">own</span> <span m="2649240">set</span>
  <span m="2649630">of</span> <span m="2649840">drawings</span> <span m="2650440">so</span>
  <span m="2650650">that</span> <span m="2650770">you</span> <span m="2650920">understand</span>
  <span m="2651550">these</span> <span m="2651850">things.</span></p><p><span m="2652970">And</span>
  <span m="2653260">the</span> <span m="2653440">important</span> <span m="2653890">thing</span>
  <span m="2654610">is</span> <span m="2654910">the</span> <span m="2655390">understanding,</span>
  <span m="2656080">the</span> <span m="2656260">ability</span> <span m="2656740">to</span>
  <span m="2656920">draw</span> <span m="2657160">these</span> <span m="2657370">pictures</span>
  <span m="2658210">which</span> <span m="2658780">contain</span> <span m="2659800">the</span>
  <span m="2659920">critical</span> <span m="2660520">information</span> <span m="2661240">about</span>
  <span m="2661570">node</span> <span m="2661900">spacings,</span> <span m="2662590">amplitudes,</span>
  <span m="2664330">shapes,</span> <span m="2666190">and</span> <span m="2666550">to</span>
  <span m="2666730">anticipate</span> <span m="2667840">when</span> <span m="2668170">you're</span>
  <span m="2668290">going</span> <span m="2668470">to</span> <span m="2668590">have</span>
  <span m="2669100">left-right</span> <span m="2669550">motion</span> <span m="2670386">or</span>
  <span m="2671160">when</span> <span m="2671330">you're</span> <span m="2671420">just</span>
  <span m="2671600">going</span> <span m="2671780">to</span> <span m="2671840">have</span>
  <span m="2673280">complicated</span> <span m="2674500">up-down</span> <span m="2674780">motions.</span>
  <span m="2675200">Because</span> <span m="2675530">there</span> <span m="2675650">could</span>
  <span m="2675800">be</span> <span m="2675920">nodes.</span> <span m="2676810">But</span>
  <span m="2677120">there</span> <span m="2677330">is</span> <span m="2677540">no</span>
  <span m="2678260">motion</span> <span m="2678880">of</span> <span m="2679040">the</span>
  <span m="2679250">center</span> <span m="2679850">of</span> <span m="2680090">this</span>
  <span m="2681170">wavepacket.</span></p><p><span m="2683620">Now,</span> <span m="2684430">this</span>
  <span m="2684640">is</span> <span m="2685600">fantastic.</span> <span m="2686500">Because</span>
  <span m="2687640">I</span> <span m="2687730">just</span> <span m="2687880">said</span>
  <span m="2688420">wavepacket.</span> <span m="2691170">Quantum</span> <span m="2691500">mechanics--</span>
  <span m="2697133">eigenfunctions</span> <span m="2698960">don't</span> <span m="2699450">move.</span>
  <span m="2701000">Superpositions</span> <span m="2701930">of</span> <span m="2702050">eigenfunctions</span>
  <span m="2702920">do</span> <span m="2703220">move.</span> <span m="2704420">If</span>
  <span m="2704600">we</span> <span m="2704720">make</span> <span m="2705050">a</span>
  <span m="2705140">superposition</span> <span m="2705920">of</span> <span m="2706040">many</span>
  <span m="2706400">eigenfunctions,</span> <span m="2707040">it</span> <span m="2707230">is</span>
  <span m="2707420">a</span> <span m="2707450">particle-like</span> <span m="2708140">state.</span>
  <span m="2710370">What</span> <span m="2710500">that</span> <span m="2711100">particle-like</span>
  <span m="2711340">state</span> <span m="2711640">will</span> <span m="2711820">do</span>
  <span m="2712060">is</span> <span m="2712210">exactly</span> <span m="2712870">what</span>
  <span m="2712990">you</span> <span m="2713140">expect</span> <span m="2715030">from</span>
  <span m="2715990">8.01.</span> <span m="2717600">The</span> <span m="2718020">particle-like</span>
  <span m="2718830">states--</span> <span m="2720300">the</span> <span m="2720390">center</span>
  <span m="2720870">of</span> <span m="2721110">the</span> <span m="2722220">wavepacket</span>
  <span m="2722640">for</span> <span m="2722790">a</span> <span m="2722880">particle-like</span>
  <span m="2723750">state</span> <span m="2724590">moves</span> <span m="2725190">according</span>
  <span m="2725580">to</span> <span m="2725700">Newton's</span> <span m="2726030">equations.</span></p><p><span
  m="2728080">So</span> <span m="2728220">I'm</span> <span m="2728430">saying</span>
  <span m="2729000">I'm</span> <span m="2729120">taking</span> <span m="2729450">away</span>
  <span m="2730200">your</span> <span m="2730350">ability</span> <span m="2730710">to</span>
  <span m="2730830">look</span> <span m="2731040">at</span> <span m="2731130">microscopic</span>
  <span m="2731850">stuff.</span> <span m="2733390">And</span> <span m="2733540">I'm</span>
  <span m="2733720">going</span> <span m="2733930">to</span> <span m="2733990">give</span>
  <span m="2734170">it</span> <span m="2734260">back</span> <span m="2734500">to</span>
  <span m="2734560">you.</span> <span m="2734710">By</span> <span m="2734830">the</span>
  <span m="2734980">end</span> <span m="2735100">of</span> <span m="2735160">the</span>
  <span m="2735250">course,</span> <span m="2736380">we're</span> <span m="2736470">going</span>
  <span m="2736590">to</span> <span m="2736720">have</span> <span m="2736900">the</span>
  <span m="2737340">time-dependent</span> <span m="2738045">Schrodinger</span> <span
  m="2738320">equation.</span> <span m="2739300">We're</span> <span m="2739420">going</span>
  <span m="2739630">to</span> <span m="2739690">be</span> <span m="2739810">able</span>
  <span m="2739990">to</span> <span m="2740050">see</span> <span m="2740410">things</span>
  <span m="2740710">move.</span> <span m="2741640">And</span> <span m="2741760">we're</span>
  <span m="2741850">going</span> <span m="2742020">to</span> <span m="2742120">see</span>
  <span m="2742390">why</span> <span m="2742660">they</span> <span m="2742810">move</span>
  <span m="2743560">and</span> <span m="2743980">how</span> <span m="2744280">they</span>
  <span m="2744430">encode</span> <span m="2744820">that</span> <span m="2745000">motion.</span></p><p><span
  m="2746840">Not</span> <span m="2747050">in</span> <span m="2747140">the</span>
  <span m="2747200">textbooks,</span> <span m="2748780">but</span> <span m="2748910">I</span>
  <span m="2749000">think</span> <span m="2749270">it's</span> <span m="2749390">something</span>
  <span m="2749750">you</span> <span m="2749900">really</span> <span m="2750170">want</span>
  <span m="2750380">to</span> <span m="2750440">be</span> <span m="2750530">able</span>
  <span m="2750710">to</span> <span m="2750830">do.</span> <span m="2751040">If</span>
  <span m="2751160">you're</span> <span m="2751250">going</span> <span m="2751430">to</span>
  <span m="2751490">understand</span> <span m="2752600">physical</span> <span m="2752990">systems</span>
  <span m="2753560">and</span> <span m="2753680">use</span> <span m="2753950">it</span>
  <span m="2754550">to</span> <span m="2754700">guide</span> <span m="2755150">your</span>
  <span m="2755300">understanding,</span> <span m="2756780">you</span> <span m="2756920">have</span>
  <span m="2757190">to</span> <span m="2757280">be</span> <span m="2757430">able</span>
  <span m="2757550">to</span> <span m="2757670">draw</span> <span m="2757910">these</span>
  <span m="2758120">pictures</span> <span m="2759140">and</span> <span m="2759380">build</span>
  <span m="2759890">a step</span> <span m="2760220">at</span> <span m="2760340">a</span>
  <span m="2760370">time.</span> <span m="2761130">And</span> <span m="2761180">so</span>
  <span m="2762040">this</span> <span m="2762320">way</span> <span m="2762480">the</span>
  <span m="2762680">equation,</span> <span m="2763450">the</span> <span m="2763520">classical</span>
  <span m="2764030">wave</span> <span m="2764300">equation,</span> <span m="2765110">gives</span>
  <span m="2765410">you</span> <span m="2765710">almost</span> <span m="2766160">all</span>
  <span m="2766580">of</span> <span m="2766760">the</span> <span m="2767150">tools</span>
  <span m="2767720">for</span> <span m="2768050">artistry</span> <span m="2769040">as</span>
  <span m="2769190">well</span> <span m="2769370">as</span> <span m="2769550">insight.</span></p><p><span
  m="2773230">OK.</span> <span m="2775200">Now,</span> <span m="2775500">in</span>
  <span m="2775710">the</span> <span m="2775950">notes,</span> <span m="2776400">there</span>
  <span m="2776760">is</span> <span m="2777000">a</span> <span m="2777150">time-lapse</span>
  <span m="2777780">movie</span> <span m="2778500">that</span> <span m="2778680">shows</span>
  <span m="2779610">what</span> <span m="2779850">a</span> <span m="2780210">two-state</span>
  <span m="2782310">wave</span> <span m="2782670">function--</span> <span m="2783972">what</span>
  <span m="2784340">a</span> <span m="2784800">two-state</span> <span m="2785490">solution</span>
  <span m="2785910">to</span> <span m="2785990">the</span> <span m="2786060">wave</span>
  <span m="2786330">equation</span> <span m="2787080">looks</span> <span m="2787290">like</span>
  <span m="2787740">if</span> <span m="2787920">you</span> <span m="2788040">have</span>
  <span m="2788280">even</span> <span m="2788700">and</span> <span m="2788880">odd</span>
  <span m="2789450">or</span> <span m="2789810">only</span> <span m="2790080">even</span>
  <span m="2790380">and</span> <span m="2790500">even</span> <span m="2791220">terms.</span></p><p><span
  m="2793420">OK.</span> <span m="2793860">Now,</span> <span m="2795370">I'm</span>
  <span m="2795480">going</span> <span m="2795570">to</span> <span m="2795670">make</span>
  <span m="2795850">some</span> <span m="2796030">assertions</span> <span m="2797410">at</span>
  <span m="2797500">the</span> <span m="2797680">end.</span> <span m="2798740">We're</span>
  <span m="2798840">coming</span> <span m="2799000">back</span> <span m="2799330">to</span>
  <span m="2799480">the</span> <span m="2799630">drum</span> <span m="2800000">problem.</span>
  <span m="2803000">And</span> <span m="2803140">suppose</span> <span m="2803920">we</span>
  <span m="2804070">have</span> <span m="2804490">a</span> <span m="2804520">rectangular</span>
  <span m="2805330">drum.</span> <span m="2808970">Well,</span> <span m="2809630">solving</span>
  <span m="2810590">the</span> <span m="2810740">differential</span> <span m="2811340">equation</span>
  <span m="2811760">for</span> <span m="2811940">this</span> <span m="2812390">rectangular</span>
  <span m="2813050">drum</span> <span m="2813770">gives</span> <span m="2814040">you</span>
  <span m="2814190">a</span> <span m="2814250">bunch</span> <span m="2814580">of</span>
  <span m="2815000">normal</span> <span m="2815420">mode</span> <span m="2815720">frequencies</span>
  <span m="2816440">that</span> <span m="2816680">depend</span> <span m="2817130">on</span>
  <span m="2817280">two</span> <span m="2817610">indices.</span></p><p><span m="2835871">And</span>
  <span m="2836380">so</span> <span m="2836770">this</span> <span m="2837040">is</span>
  <span m="2837760">the</span> <span m="2837910">geometric</span> <span m="2838660">structure</span>
  <span m="2839140">of</span> <span m="2839770">the</span> <span m="2840370">drum.</span>
  <span m="2841900">And</span> <span m="2842020">these</span> <span m="2842230">are</span>
  <span m="2842290">the</span> <span m="2842410">quantum</span> <span m="2842740">numbers.</span>
  <span m="2844410">And</span> <span m="2844500">these</span> <span m="2844710">are</span>
  <span m="2844770">the</span> <span m="2844890">frequencies.</span> <span m="2847850">And</span>
  <span m="2847970">it's</span> <span m="2848120">going</span> <span m="2848190">to</span>
  <span m="2848330">make</span> <span m="2848570">a</span> <span m="2848630">whole</span>
  <span m="2848810">bunch</span> <span m="2849050">of</span> <span m="2849110">frequencies</span>
  <span m="2849740">that</span> <span m="2849890">are</span> <span m="2849980">not</span>
  <span m="2850250">integer</span> <span m="2850550">multiples</span> <span m="2851060">of</span>
  <span m="2851180">each</span> <span m="2851360">other</span> <span m="2851810">or</span>
  <span m="2852020">of</span> <span m="2852230">any</span> <span m="2853340">simpler</span>
  <span m="2853940">thing.</span> <span m="2854960">And</span> <span m="2855080">that's</span>
  <span m="2855290">why</span> <span m="2855440">it</span> <span m="2855500">sounds</span>
  <span m="2855800">horrible.</span></p><p><span m="2859980">It's</span> <span m="2860130">perhaps</span>
  <span m="2861000">a</span> <span m="2861060">little</span> <span m="2861240">bit</span>
  <span m="2861390">like</span> <span m="2861630">playing</span> <span m="2862110">a</span>
  <span m="2862140">violin</span> <span m="2862560">with</span> <span m="2862770">a</span>
  <span m="2862830">saw.</span> <span m="2864510">It</span> <span m="2864660">will</span>
  <span m="2864800">sound</span> <span m="2865130">terrible.</span> <span m="2867200">You</span>
  <span m="2867320">would</span> <span m="2867470">never</span> <span m="2867740">do</span>
  <span m="2867980">it.</span> <span m="2868700">But</span> <span m="2869000">you</span>
  <span m="2869090">would</span> <span m="2869240">also</span> <span m="2869540">never</span>
  <span m="2869840">build</span> <span m="2870440">a</span> <span m="2870530">square</span>
  <span m="2871010">or</span> <span m="2871130">rectangular</span> <span m="2871760">drum.</span>
  <span m="2872490">But</span> <span m="2873320">the</span> <span m="2873440">noise</span>
  <span m="2874190">that</span> <span m="2874370">you</span> <span m="2874550">make</span>
  <span m="2875480">tells</span> <span m="2876140">immediately</span> <span m="2877650">not</span>
  <span m="2877910">just</span> <span m="2878870">what</span> <span m="2879230">the</span>
  <span m="2880070">shape</span> <span m="2880580">of</span> <span m="2880700">the</span>
  <span m="2880820">instrument</span> <span m="2881270">is</span> <span m="2882440">but</span>
  <span m="2882620">how</span> <span m="2882920">it</span> <span m="2882980">was</span>
  <span m="2883130">played.</span></p><p><span m="2883940">For</span> <span m="2884150">example,</span>
  <span m="2884690">suppose</span> <span m="2885950">you</span> <span m="2886100">had</span>
  <span m="2886400">an</span> <span m="2886550">elliptical</span> <span m="2887120">drum.</span>
  <span m="2889320">That'll</span> <span m="2889590">sound</span> <span m="2889860">terrible,</span>
  <span m="2890250">too.</span> <span m="2890940">But</span> <span m="2891360">here</span>
  <span m="2891570">are</span> <span m="2891630">the</span> <span m="2891750">two</span>
  <span m="2891960">foci.</span> <span m="2893070">I'm</span> <span m="2893250">not</span>
  <span m="2893400">so</span> <span m="2893580">sure</span> <span m="2893850">it'll</span>
  <span m="2894000">sound</span> <span m="2894270">terrible</span> <span m="2894780">if</span>
  <span m="2894870">you</span> <span m="2894990">hit</span> <span m="2895110">it</span>
  <span m="2895230">here</span> <span m="2895690">or</span> <span m="2895830">here.</span>
  <span m="2898650">And</span> <span m="2899250">certainly,</span> <span m="2899790">if</span>
  <span m="2899910">you</span> <span m="2899990">are</span> <span m="2900090">a</span>
  <span m="2900120">circular</span> <span m="2900660">drum,</span> <span m="2901720">if</span>
  <span m="2901740">you</span> <span m="2901890">hit</span> <span m="2902100">it</span>
  <span m="2902190">in</span> <span m="2902340">the</span> <span m="2902430">middle</span>
  <span m="2903360">as</span> <span m="2903480">opposed</span> <span m="2903780">to</span>
  <span m="2903900">on</span> <span m="2903990">the</span> <span m="2904110">edges,</span>
  <span m="2904470">it'll</span> <span m="2904650">sound</span> <span m="2904950">different.</span>
  <span m="2906670">The</span> <span m="2906820">spectral</span> <span m="2907390">content</span>
  <span m="2907930">will</span> <span m="2908080">be</span> <span m="2908200">the</span>
  <span m="2908290">same.</span> <span m="2909110">But</span> <span m="2909190">the</span>
  <span m="2909370">amplitudes</span> <span m="2910030">of</span> <span m="2910180">each</span>
  <span m="2910630">component</span> <span m="2911200">will</span> <span m="2911380">be</span>
  <span m="2911470">different.</span></p><p><span m="2912830">And</span> <span m="2912880">so</span>
  <span m="2913390">in</span> <span m="2913540">quantum</span> <span m="2913870">mechanics,</span>
  <span m="2914930">you</span> <span m="2915010">use</span> <span m="2915310">the</span>
  <span m="2915430">same</span> <span m="2915940">sort</span> <span m="2916570">of</span>
  <span m="2917560">instinct</span> <span m="2918370">as</span> <span m="2918640">you</span>
  <span m="2918790">develop</span> <span m="2919300">as</span> <span m="2919450">a</span>
  <span m="2919510">musician</span> <span m="2920710">in</span> <span m="2920860">order</span>
  <span m="2921070">to</span> <span m="2922210">figure</span> <span m="2922570">out</span>
  <span m="2922780">how</span> <span m="2923110">this</span> <span m="2923770">system</span>
  <span m="2924310">is</span> <span m="2924430">going</span> <span m="2924580">to</span>
  <span m="2924670">respond</span> <span m="2925180">to</span> <span m="2925300">what</span>
  <span m="2925420">you</span> <span m="2925540">do</span> <span m="2925730">to</span>
  <span m="2925840">it.</span> <span m="2928610">And</span> <span m="2928710">that's</span>
  <span m="2928980">pretty</span> <span m="2929250">powerful.</span> <span m="2932320">So</span>
  <span m="2933010">many</span> <span m="2933400">of</span> <span m="2933520">you</span>
  <span m="2933700">are</span> <span m="2933880">musicians.</span> <span m="2934540">And</span>
  <span m="2934720">you</span> <span m="2934870">know</span> <span m="2935200">instinctively</span>
  <span m="2937370">what's</span> <span m="2937640">wrong</span> <span m="2938000">when</span>
  <span m="2938150">you</span> <span m="2938270">do</span> <span m="2938450">something</span>
  <span m="2939130">that's</span> <span m="2939350">not</span> <span m="2939560">quite</span>
  <span m="2939860">right,</span> <span m="2941450">or</span> <span m="2942290">your</span>
  <span m="2943130">instrument</span> <span m="2943610">is</span> <span m="2943730">out</span>
  <span m="2943880">of</span> <span m="2943970">tune.</span></p><p><span m="2944600">But</span>
  <span m="2945590">in</span> <span m="2945710">quantum</span> <span m="2946010">mechanics,</span>
  <span m="2946490">all</span> <span m="2946700">of</span> <span m="2946790">those</span>
  <span m="2947120">insights</span> <span m="2947690">will</span> <span m="2947960">come</span>
  <span m="2948260">to</span> <span m="2948350">bear.</span> <span m="2949880">Not</span>
  <span m="2950180">in</span> <span m="2950240">the</span> <span m="2950330">textbooks.</span>
  <span m="2953240">Because</span> <span m="2953510">the</span> <span m="2953600">textbooks</span>
  <span m="2954230">tell</span> <span m="2954470">you</span> <span m="2954650">about</span>
  <span m="2954890">exactly</span> <span m="2955370">solved</span> <span m="2955640">problems.</span>
  <span m="2957140">And</span> <span m="2957320">then</span> <span m="2957500">they</span>
  <span m="2957680">tell</span> <span m="2957920">you</span> <span m="2958940">how</span>
  <span m="2959180">to</span> <span m="2959270">do</span> <span m="2959570">spectra</span>
  <span m="2960050">that</span> <span m="2960230">are</span> <span m="2960350">too</span>
  <span m="2960560">perfect</span> <span m="2961040">for</span> <span m="2961310">anybody</span>
  <span m="2961910">else</span> <span m="2962120">to</span> <span m="2962300">observe.</span>
  <span m="2963940">And</span> <span m="2964900">you</span> <span m="2965290">won't</span>
  <span m="2965530">see</span> <span m="2965710">those</span> <span m="2965890">spectra.</span>
  <span m="2966490">And</span> <span m="2966650">they</span> <span m="2966790">don't</span>
  <span m="2967000">tell</span> <span m="2967240">you</span> <span m="2967390">what</span>
  <span m="2967600">the</span> <span m="2967720">spectra</span> <span m="2968290">you</span>
  <span m="2968440">will</span> <span m="2968710">observe</span> <span m="2969970">tell</span>
  <span m="2970240">you</span> <span m="2970420">about</span> <span m="2970750">the</span>
  <span m="2970840">system</span> <span m="2971800">in</span> <span m="2971950">question.</span></p><p><span
  m="2972610">OK.</span> <span m="2973300">So</span> <span m="2973480">I</span> <span
  m="2973600">should</span> <span m="2973780">stop</span> <span m="2974170">now.</span>
  <span m="2975070">And</span> <span m="2978100">I'm</span> <span m="2978220">going</span>
  <span m="2978390">to</span> <span m="2978460">be</span> <span m="2979480">generating</span>
  <span m="2980260">Problem</span> <span m="2980760">Set</span> <span m="2981250">2,</span>
  <span m="2981460">which will</span> <span m="2981640">be</span> <span m="2981760">posted</span>
  <span m="2982180">on</span> <span m="2982330">Friday.</span> <span m="2983230">Problem</span>
  <span m="2983620">Set</span> <span m="2983740">1</span> <span m="2983980">is</span>
  <span m="2984130">due</span> <span m="2984940">this</span> <span m="2985150">Friday.</span>
  <span m="2986130">And--</span> <span m="2988650">Good.</span> <span m="2989080">Thank</span>
  <span m="2989320">you.</span></p>
type: course
uid: 305ef304673ee0782f6ea89ad959e4fd

---
None
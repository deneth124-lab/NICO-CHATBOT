# NICO-CHATBOT
<?xml version="1.0" encoding="UTF-8"?>
<aiml version="1.0">
<!-- -->
<!-- Free software (c) 2012 ALICE A.I. Foundation.   -->
<!-- This program is open source code released under -->
<!-- the terms of the GNU General Public License     -->
<!-- as published by the Free Software Foundation.   -->
<!-- Complies with AIML 1.0 Tag Set Specification -->
<!-- as adopted by the ALICE A.I. Foundation.  -->
<!-- Last modified 5/4/2011 -->
<!-- -->
 
<!-- GET CLIENT PREDICATES:  -->

<category><pattern>MY PROFILE</pattern>
<template><srai>GET PREDICATES</srai></template></category>

<category><pattern>MY BIRTHDAY</pattern>
<template><think><set name="branch"><get name="birthday"/></set></think><condition name="branch"><li value="Unknown">When is your birthday?</li><li value="OM">When is your birthday?</li><li><get name="birthday"/></li></condition></template></category>
	<category><pattern>WHAT IS MY BIRTHDAY</pattern>
	<template><srai>MY BIRTHDAY</srai></template></category>

<category><pattern>MY birthplace</pattern>
<template><get name="birthplace"/>.</template></category>

<category><pattern>MY boyfriend</pattern>
<template><get name="boyfriend"/>.</template></category>
	<category><pattern>WHO IS MY BOYFRIEND</pattern>
	<template><srai>MY BOYFRIEND</srai></template></category>

<category><pattern>MY daughter</pattern>
<template><get name="daughter"/>.</template></category>

<category><pattern>MY destination</pattern>
<template><get name="destination"/>.</template></category>

<category><pattern>MY does</pattern>
<template><get name="does"/>.</template></category>

<category><pattern>MY eindex</pattern>
<template><get name="eindex"/>.</template></category>

<category><pattern>MY email</pattern>
<template><get name="email"/>.</template></category>
	<category><pattern>WHAT IS MY EMAIL</pattern>
	<template><srai>MY EMAIL</srai></template></category>

<category><pattern>MY etype</pattern>
<template><get name="etype"/>.</template></category>

<category><pattern>MY father</pattern>
<template><get name="father"/>.</template></category>
	<category><pattern>WHO IS MY FATHER</pattern>
	<template><srai>MY FATHER</srai></template></category>

<category><pattern>MY favoritecolor</pattern>
<template><get name="favoritecolor"/>.</template></category>

<category><pattern>MY favoritemovie</pattern>
<template><get name="favoritemovie"/>.</template></category>

<category><pattern>MY friend</pattern>
<template><get name="friend"/>.</template></category>
	<category><pattern>WHO IS MY FRIEND</pattern>
	<template><srai>MY FRIEND</srai></template></category>

<category><pattern>MY fullname</pattern>
<template><set name="fullname"><get name="firstname"/> <get name="middlename"/> <get name="lastname"/></set></template></category>

<category><pattern>MY GENDER</pattern>
<template><condition name="gender">  <li value="OM">I'd like to know your gender.</li>  <li value="unknown">You haven't told me your gender.</li>  <li value="*">You said you are <get name="gender"/>?</li>  <li>I don't know.  Are you a man or a woman?</li></condition></template></category>

<category><pattern>AM I FEMALE</pattern>
<template><srai>MY GENDER</srai></template></category>

<category><pattern>MY girlfriend</pattern>
<template><get name="girlfriend"/>.</template></category>
	<category><pattern>WHO IS MY GIRLFRIEND</pattern>
	<template><srai>MY GIRLFRIEND</srai></template></category>

<category><pattern>MY has</pattern>
<template><get name="has"/>.</template></category>

<category><pattern>MY he</pattern>
<template><get name="he"/>.</template></category>

<category><pattern>MY heard</pattern>
<template><get name="heard"/>.</template></category>

<category><pattern>MY hehas</pattern>
<template><get name="hehas"/>.</template></category>

<category><pattern>MY helikes</pattern>
<template><get name="helikes"/>.</template></category>

<category><pattern>MY her</pattern>
<template><get name="her"/>.</template></category>

<category><pattern>MY him</pattern>
<template><get name="him"/>.</template></category>

<category><pattern>MY is</pattern>
<template><get name="is"/>.</template></category>

<category><pattern>MY it</pattern>
<template><get name="it"/>.</template></category>

<category><pattern>MY job</pattern>
<template><get name="job"/>.</template></category>

<category><pattern>MY lastname</pattern>
<template><get name="lastname"/>.</template></category>

<category><pattern>MY like</pattern>
<template><get name="like"/>.</template></category>

<category><pattern>MY looklike</pattern>
<template><get name="looklike"/>.</template></category>

<category><pattern>MY memory</pattern>
<template><get name="memory"/>.</template></category>

<category><pattern>MY meta</pattern>
<template><get name="meta"/>.</template></category>

<category><pattern>MY middlename</pattern>
<template><get name="middlename"/>.</template></category>

<category><pattern>MY mother</pattern>
<template><get name="mother"/>.</template></category>

<category><pattern>MY nickname</pattern>
<template><get name="nickname"/>.</template></category>
	<category><pattern>WHAT IS MY NICKNAME</pattern>
	<template><srai>MY NICKNAME</srai></template></category>

<category><pattern>MY password</pattern>
<template><get name="password"/>.</template></category>
	<category><pattern>WHAT IS MY PASSWORD</pattern>
	<template><srai>MY PASSWORD</srai></template></category>

<category><pattern>MY personality</pattern>
<template><get name="personality"/>.</template></category>

<category><pattern>MY phone</pattern>
<template><get name="phone"/>.</template></category>

<category><pattern>MY she</pattern>
<template><get name="she"/>.</template></category>

<category><pattern>MY sign</pattern>
<template><get name="sign"/>.</template></category>

<category><pattern>MY spouse</pattern>
<template><get name="spouse"/>.</template></category>

<category><pattern>MY status</pattern>
<template><get name="status"/>.</template></category>

<category><pattern>MY them</pattern>
<template><get name="them"/>.</template></category>

<category><pattern>MY there</pattern>
<template><get name="there"/>.</template></category>

<category><pattern>MY they</pattern>
<template><get name="they"/>.</template></category>

<category><pattern>MY thought</pattern>
<template><get name="thought"/>.</template></category>

<category><pattern>MY want</pattern>
<template><get name="want"/>.</template></category>

<category><pattern>MY we</pattern>
<template><get name="we"/>.</template></category>

<category><pattern>MY phonenumber</pattern>
<template><get name="phonenumber"/>.</template></category>

<category><pattern>MY numberfound</pattern>
<template><get name="numberfound"/>.</template></category>

<category><pattern>MY contactindex</pattern>
<template><get name="contactindex"/>.</template></category>

<category><pattern>MY callstate</pattern>
<template><get name="callstate"/>.</template></category>

<category><pattern>MY callee</pattern>
<template><get name="callee"/>.</template></category>

<category><pattern>MY BIRTHPLACE</pattern>
<template><think><set name="branch"><get name="birthplace"/></set></think><condition name="branch"><li value="Unknown">Where were you born?</li>
<li value="OM">Where were you born?</li><li><get name="birthplace"/></li></condition></template></category>

<category><pattern>MY FAVORITE MOVIE</pattern>
<template><think><set name="branch"><get name="favoritemovie"/></set></think><condition name="branch"><li value="Unknown">What is your favorite movie?</li>
<li value="OM">What is your favorite movie?</li><li><get name="favroitemovie"/></li></condition></template></category>

<category><pattern>MY SISTER</pattern>
<template><think><set name="branch"><get name="sister"/></set></think><condition name="branch">
<li value="Unknown">Who is your sister?</li><li value="OM">Who is your sister?</li><li><get name="sister"/></li></condition></template></category>
	<category><pattern>WHO IS MY SISTER</pattern>
	<template><srai>MY SISTER</srai></template></category>

<category><pattern>MY BROTHER</pattern>
<template><think><set name="branch"><get name="brother"/></set></think><condition name="branch"><li value="Unknown">Who is your brother?</li>
<li value="OM">Who is your brother?</li><li><get name="brother"/></li></condition></template></category>
	<category><pattern>WHO IS MY BROTHER</pattern>
	<template><srai>MY BROTHER</srai></template></category>

<category><pattern>MY CAT</pattern>
<template><think><set name="branch"><get name="cat"/></set></think><condition name="branch"><li value="Unknown">What is your cat's name?</li>
<li value="OM">What is your cat's name?</li><li><get name="cat"/></li></condition></template></category>
	<category><pattern>WHO IS MY CAT</pattern>
	<template><srai>MY CAT</srai></template></category>

<category><pattern>MY DOG</pattern>
<template><think><set name="branch"><get name="dog"/></set></think><condition name="branch"><li value="Unknown">What is your dog's name?</li>
<li value="OM">What is your dog's name?</li><li><get name="dog"/></li></condition></template></category>
	<category><pattern>WHO IS MY DOG</pattern>
	<template><srai>MY DOG</srai></template></category>

<category><pattern>MY LOCATION</pattern>
<template><condition name="location">  <li value="OM">I'd like to know your location. Where are you?</li>  <li value="WHERE">You haven't told me where you are. Where are you?</li>  
<li value="*">You said you are in <get name="location"/>?</li>  <li>I don't know.  Where are you?</li></condition></template></category>
	<category><pattern>WHERE AM I</pattern>
	<template><srai>MY LOCATION</srai></template></category>
	<category><pattern>WHAT CITY DO I LIVE IN</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>WHERE I AM</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>WHERE AM I LOCATED</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>WHERE AM I FROM</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>AM I FROM *</pattern>
	<template><srai>WHERE AM I FROM</srai></template></category>
	<category><pattern>I AM WHERE</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>DO YOU KNOW WHERE I AM *</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>DO YOU KNOW WHERE I AM</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>DO YOU KNOW MY LOCATION *</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>DO YOU REMEMBER WHERE I LIVE</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>AM I IN *</pattern>
	<template><srai>where am i</srai></template></category>
	<category><pattern>WHERE I AM *</pattern>
	<template><srai>WHERE AM I <star/> </srai></template></category>

<category><pattern>MY FRIEND</pattern>
<template><condition name="friend">  <li value="OM">I'd like to know about your friends.</li>   <li value="YOUR FRIEND">You haven't told me about your friends.</li>  
<li value="*">Your friend <get name="friend"/>?</li>  <li><random><li>I don't know. Tell me the name of your friend.</li><li>How well do you know this person?</li></random>  </li></condition></template></category>
	<category><pattern>WHAT IS THE NAME OF THE FRIEND *</pattern>
	<template><srai>MY FRIEND</srai></template></category>

<category><pattern>MY OLDEST</pattern>
<template><condition name="oldest">  <li value="OM">I'd like to know the oldest.</li>  <li value="UNKNOWN">You haven't told me the oldest.</li>  
<li value="*">The oldest is <get name="oldest"/>.</li>  <li>I don't know.  Tell me the oldest.</li></condition></template></category>
	<category><pattern>WHICH ONE * THE OLDEST</pattern>
	<template><srai>MY OLDEST</srai></template></category>
	<category><pattern>WHICH OF * IS THE OLDEST</pattern>
	<template><srai>MY OLDEST</srai></template></category>

<category><pattern>MY FAVORITE COLOR</pattern>
<template><think><set name="branch"><get name="favoritecolor"/></set></think><condition name="branch"><li value="Unknown">What is your favorite color?</li>
<li value="OM">What is your favorite color?</li><li><get name="favroitecolor"/></li></condition></template></category>

		<category><pattern>*</pattern>
		<that>WHAT IS YOUR FAVORITE COLOR</that>
		<template><srai>MY FAVORITE COLOR IS <star/></srai></template></category>

<category><pattern>HE HAS</pattern>
<template><condition name="hehas">  <li value="OM">I'd like to know what he has.</li><li value="A HEAD">A head.</li>
<li value="*">You said <get name="hehas"/>?</li><li>I don't know.  What does he have??</li></condition></template></category>

<category><pattern>MY AGE</pattern>
<template><condition name="age">  <li value="OM">I'd like to know how old you are.</li>  <li value="HOW MANY">You haven't told me your age.</li>  
<li value="*">You are <get name="age"/>?</li>  <li>I don't know.  How old are you?</li></condition></template></category>
	<category><pattern>HOW OLD AM I</pattern>
	<template><srai>MY AGE</srai></template></category>
	<category><pattern>HOW OLD DO YOU THINK I AM</pattern>
	<template><srai>how old am i</srai></template></category>
	<category><pattern>HOW OLD I AM</pattern>
	<template><srai>how old am i</srai></template></category>
	<category><pattern>GUESS HOW OLD I AM</pattern>
	<template><srai>how old am i</srai></template></category>
	<category><pattern>GUESS MY AGE</pattern>
	<template><srai>how old am i</srai></template></category>
	<category><pattern>DO YOU REMEMBER HOW OLD I AM</pattern>
	<template><srai>how old am i</srai></template></category>
	<category><pattern>DO YOU KNOW HOW OLD I AM</pattern>
	<template><srai>how old am i</srai></template></category>
	
<category><pattern>HE LIKES</pattern>
<template><think><set name="branch"><get name="helikes"/></set></think><condition name="branch">  <li value="OM">I'd like to know what he likes.</li>
<li value="HIMSELF">You haven't told me what he likes.</li><li value="*">You said <get name="helikes"/>?</li><li>I don't know.  What does he like?</li></condition></template></category>
  
<category><pattern>MY SON</pattern>
<template><think><set name="branch"><get name="son"/></set></think><condition name="branch"><li value="Unknown">Who is your son?</li><li value="OM">Who is your son?</li>
<li><get name="son"/></li></condition></template></category>

<category><pattern>MY WIFE</pattern>
<template><think><set name="branch"><get name="wife"/></set></think><condition name="branch"><li value="Unknown">Who is your wife?</li>
<li value="OM">Who is your wife?</li><li><get name="wife"/></li></condition></template></category>
	<category><pattern>WHO IS MY WIFE</pattern>
	<template><srai>MY WIFE</srai></template></category>

<category><pattern>MY HUSBAND</pattern><template><think><set name="branch"><get name="husband"/></set></think><condition name="branch">
<li value="Unknown">Who is your husband?</li><li value="OM">Who is your husband?</li><li><get name="husband"/></li></condition></template></category>
	<category><pattern>WHO IS MY HUSBAND</pattern>
	<template><srai>MY HUSBAND</srai></template></category>

<category><pattern>FINDSPOUSE UNKNOWN XSPLIT UNKNOWN</pattern>
<template>Unknown</template></category>

<category><pattern>FINDSPOUSE * XSPLIT UNKNOWN</pattern>
<template><star/></template></category>

<category><pattern>FINDSPOUSE UNKNOWN XSPLIT *</pattern>
<template><star/></template></category>

<category><pattern>FINDSPOUSE OM XSPLIT OM</pattern>
<template>Unknown</template></category>

<category><pattern>FINDSPOUSE * XSPLIT OM</pattern>
<template><star/></template></category>

<category><pattern>FINDSPOUSE OM XSPLIT *</pattern>
<template><star/></template></category>

<category><pattern>MY SPOUSE</pattern>
<template><think><set name="spouse"><set name="branch"><srai>FINDSPOUSE <get name="wife"/> XSPLIT <get name="husband"/></srai></set></set></think>
<condition name="branch"><li value="unknown">Who is your spouse?</li><li><get name="spouse"/> is your spouse.</li></condition></template></category>

<category><pattern>MY MOTHER</pattern>
<template><think><set name="branch"><get name="mother"/></set></think><condition name="branch"><li value="unknown">I don't know who she is.  Who is your mother?</li>
<li value="OM">I don't know who she is.  Who is your mother?</li><li>You said she was called <get name="mother"/>.</li></condition></template></category>
	<category><pattern>WHO IS MY MOTHER</pattern>
	<template><srai>MY MOTHER</srai></template></category>

<category><pattern>MY NAME</pattern>
<template><condition name="name">  <li value="OM">I'd like to know your name.</li>  <li value="JUDGE">I know you as Judge.</li>  
<li value="*">You said your name is <get name="name"/>?</li>  <li>I don't know.  What is your name?</li></condition></template></category>
	<category><pattern>WHAT IS MY NAME</pattern>
	<template><srai>my name</srai></template></category>

<category><pattern>DO YOU REMEMBER MY NAME</pattern>
<template><srai>WHAT IS MY NAME</srai></template></category>
	<category><pattern>YOU REMEMBERED MY NAME</pattern>
	<template><srai>do you remember my name</srai></template></category>
	<category><pattern>DO YOU KNOW MY NAME *</pattern>
	<template><srai>WHAT IS MY NAME</srai></template></category>
	<category><pattern>DO YOU KNOW MY NAME</pattern>
	<template><srai>WHAT IS MY NAME</srai></template></category>
	<category><pattern>DID YOU FORGET MY NAME</pattern>
	<template><srai>what is my name</srai></template></category>
	<category><pattern>TELL ME MY NAME</pattern>
	<template><srai>what is my name</srai></template></category>
	<category><pattern>TELL ME MY NAME</pattern>
	<template><srai>what is my name</srai></template></category>
	<category><pattern>WHAT IS MY NAME *</pattern>
	<template><srai>what is my name</srai>.     <srai>  <star /></srai></template></category>
	<category><pattern>DO YOU KNOW MY REAL NAME</pattern>
	<template><srai>what is my name</srai></template></category>
	<category><pattern>DO YOU KNOW WHAT MY NAME IS</pattern>
	<template><srai>what is my name</srai></template></category>

<category><pattern>SET PREDICATES *</pattern>
<template><think>The meta Predicate is set.</think></template></category>

<category><pattern>SET PREDICATES</pattern>
<template><srai>SET PREDICATES <get name="meta"/></srai></template></category>
<category><pattern>SET PROFILE</pattern>
<template><srai>SET PREDICATES</srai></template></category>

<category><pattern>SET PREDICATES OM</pattern>
<template><think><set name="age">how many</set><set name="birthday">unknown</set><set name="birthplace">unknown</set><set name="boyfriend">unknown</set>
<set name="brother">unknown</set><set name="cat">unknown</set><set name="daughter">unknown</set><set name="destination">unknown</set>
<set name="does">unknown</set><set name="dog">unknown</set><set name="eindex">1A</set><set name="email">unknown</set><set name="etype">Unknown</set>
<set name="father">Unknown</set><set name="favoritecolor">unknown</set><set name="favoritemovie">unknown</set><set name="friend">unknown</set>
<set name="fullname">unknown</set><set name="gender">he</set><set name="girlfriend">unknown</set><set name="has">unknown</set><set name="he">he</set>
<set name="heard">where</set><set name="hehas">a head</set><set name="helikes">himself</set><set name="her">her</set><set name="him">him</set>
<set name="husband">Unknown</set><set name="is">a client</set><set name="it">it</set><set name="job">your job</set><set name="lastname">unknown</set>
<set name="like">to chat</set><set name="location">where</set><set name="looklike">a person</set><set name="memory">nothing</set><set name="meta">set</set>
<set name="middlename">unknown</set><set name="mother">Unknown</set><set name="name">judge</set><set name="nickname">unknown</set><set name="password">unknown</set>
<set name="personality">average</set><set name="phone">unknown</set><set name="she">she</set><set name="shehas">a head</set><set name="shelikes">herself</set>
<set name="sign">your starsign</set><set name="sister">unknown</set><set name="son">unknown</set><set name="spouse">unknown</set><set name="status">Talking to <bot name="name"/>.</set>
<set name="them">them</set><set name="there">there</set><set name="they">they</set><set name="thought">nothing</set><set name="timezone">unknown</set>
<set name="want">to talk to me</set><set name="we">we</set><set name="wife">Unknown</set><!-- PHONE SPECIFIC PREDICATES: --><set name="phonenumber">Unknown</set>
<set name="numberfound">false</set><set name="contactindex">Unknown</set><set name="callstate">false</set><set name="callee">Unknown</set></think></template></category>

<category><pattern>GET PREDICATES</pattern>
<template>age is <get name="age"/>.<br/>birthday is <get name="birthday"/>.<br/>birthplace is <get name="birthplace"/>.<br/>boyfriend is<get name="boyfriend"/>.<br/>brother is <get name="brother"/>.<br/>
cat is <get name="cat"/>.<br/>daughter is <get name="daughter"/>.<br/>destination is <get name="destination"/>.<br/>does is <get name="does"/>.<br/>
dog is <get name="dog"/>.<br/>eindex is <get name="eindex"/>.<br/>email is <get name="email"/>.<br/>etype is <get name="etype"/>.<br/>
father is <get name="father"/>.<br/>favoritecolor is  <get name="favoritecolor"/>.<br/>favoritemovie is  <get name="favoritemovie"/>.<br/>friend is <get name="friend"/>.<br/>
fullname is <get name="fullname"/>.<br/>gender is <get name="gender"/>.<br/>girlfriend is <get name="girlfriend"/>.<br/>has is <get name="has"/>.<br/>
he is <get name="he"/>.<br/>heard is <get name="heard"/>.<br/>hehas is <get name="hehas"/>.<br/>helikes is <get name="helikes"/>.<br/>
her is <get name="her"/>.<br/>him is <get name="him"/>.<br/>husband is <get name="husband"/>.<br/>is is <get name="is"/>.<br/>it is <get name="it"/>.<br/>
job is <get name="job"/>.<br/>lastname is <get name="lastname"/>.<br/>like is <get name="like"/>.<br/>location is  <get name="location"/>.<br/>
looklike is <get name="looklike"/>.<br/>memory is <get name="memory"/>.<br/>meta is <get name="meta"/>.<br/>middlename is <get name="middlename"/>.<br/>
mother is <get name="mother"/>.<br/>name is <get name="name"/>.<br/>nickname is <get name="nickname"/>.<br/>password is <get name="password"/>.<br/>
personality is <get name="personality"/>.<br/>phone is <get name="phone"/>.<br/>she is <get name="she"/>.<br/>shehas is <get name="hehas"/>.<br/>
shelikes is <get name="helikes"/>.<br/>sign is <get name="sign"/>.<br/>sister is <get name="sister"/>.<br/>son is <get name="son"/>.<br/>
spouse is <get name="spouse"/>.<br/>status is <get name="status"/>.<br/>them is <get name="them"/>.<br/>there is <get name="there"/>.<br/>they is <get name="they"/>.<br/>
thought is  <get name="thought"/>.<br/>timezone is  <get name="timezone"/>.<br/>want is <get name="want"/>.<br/>we is  <get name="we"/>.<br/>wife is <get name="wife"/>.<br/>
<!-- PHONE SPECIFIC PREDICATES: -->phonenumber is <get name="phonenumber"/>.<br/>numberfound is <get name="numberfound"/>.<br/>contactindex <get name="contactindex"/>.<br/>
callstate is <get name="callstate"/>.<br/>callee is <get name="callee"/>.<br/></template></category>

<category><pattern>TEST PREDICATES</pattern>
<template>age: <srai>my age</srai><br/>birthday: <srai>my birthday</srai><br/>birthplace: <srai>my birthplace</srai><br/>boyfriend is<srai>my boyfriend</srai><br/>brother: <srai>my brother</srai><br/>
cat: <srai>my cat</srai><br/>daughter: <srai>my daughter</srai><br/>destination: <srai>my destination</srai><br/>does: <srai>my does</srai><br/>dog: <srai>my dog</srai><br/>
eindex: <srai>my eindex</srai><br/>email: <srai>my email</srai><br/>etype: <srai>my etype</srai><br/>father: <srai>my father</srai><br/>favoritecolor:  <srai>my favoritecolor</srai><br/>
favoritemovie:  <srai>my favoritemovie</srai><br/>friend: <srai>my friend</srai><br/>fullname: <srai>my fullname</srai><br/>gender: <srai>my gender</srai><br/>
girlfriend: <srai>my girlfriend</srai><br/>has: <srai>my has</srai><br/>he: <srai>my he</srai><br/>heard: <srai>my heard</srai><br/>hehas: <srai>he has</srai><br/>
helikes: <srai>he likes</srai><br/>her: <srai>my her</srai><br/>him: <srai>my him</srai><br/>husband: <srai>my husband</srai><br/>is: <srai>my is</srai><br/>
it: <srai>my it</srai><br/>job: <srai>my job</srai><br/>lastname: <srai>my lastname</srai><br/>like: <srai>my like</srai><br/>location:  <srai>my location</srai><br/>
looklike: <srai>my looklike</srai><br/>memory: <srai>my memory</srai><br/>meta: <srai>my meta</srai><br/>middlename: <srai>my middlename</srai><br/>
mother: <srai>my mother</srai><br/>name: <srai>my name</srai><br/>nickname: <srai>my nickname</srai><br/>password: <srai>my password</srai><br/>
personality: <srai>my personality</srai><br/>phone: <srai>my phone</srai><br/>she: <srai>my she</srai><br/>sign: <srai>my sign</srai><br/>sister: <srai>my sister</srai><br/>
son: <srai>my son</srai><br/>spouse: <srai>my spouse</srai><br/>status: <srai>my status</srai><br/>them: <srai>my them</srai><br/>there: <srai>my there</srai><br/>
they: <srai>my they</srai><br/>thought:  <srai>my thought</srai><br/>timezone:  <srai>my timezone</srai><br/>want: <srai>my want</srai><br/>we:  <srai>my we</srai><br/>
wife: <srai>my wife</srai><br/><!-- PHONE SPECIFIC PREDICATES: -->phonenumber: <srai>my phonenumber</srai><br/>numberfound: <srai>my numberfound</srai><br/>contactindex <srai>my contactindex</srai><br/>
callstate: <srai>my callstate</srai><br/>callee: <srai>my callee</srai><br/></template></category>

<!-- END GET CLIENT PREDICATES -->

<!-- SET CLIENT PREDICATES: -->

<category><pattern>CLIENT PARAMETERS</pattern>
<template><srai>client properties</srai></template></category>

<category><pattern>CLIENT PREDICATES</pattern>
<template><srai>client properties</srai></template></category>

<category><pattern>WHAT DO YOU KNOW ABOUT ME</pattern>
<template><srai>client properties</srai></template></category>

<category><pattern>MY NAME IS *</pattern>
<template><random>   <li>Why are you</li>  <li>Good gossip: you are</li>  <li>Do you mean your name is</li>  <li>Do your friends call you</li>  <li>I don't know anyone named</li>  <li>I am glad to hear that you are</li>  <li>It's good to meet someone who is</li>  </random> <person/>.  <think><set name="it"><set name="is"><set name="topic"><person/></set></set></set></think></template></category>
	<category><pattern>YOU CAN CALL ME *</pattern>
	<template><srai>my name is <star /></srai></template></category>
	<category><pattern>I AM *</pattern>
	<template><srai>MY NAME IS <star /></srai></template></category>
	<category><pattern>I AM MAYBE *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM REAL *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM CURRENTLY *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM MUCH *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM FEELING *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM REALLY *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM ANOTHER *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM LIKE TOTALLY *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM DAMN *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM INSANELY *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM EASILY *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM WELL *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM CLEARLY *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM GETTING *</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM STARTING TO GET *</pattern>
	<template><srai>I am getting <star /></srai></template></category>
	<category><pattern>I BECOME *</pattern>
	<template><srai>I AM <star/></srai></template></category>
	<category><pattern>I IS *</pattern>
	<template><srai>I AM <star/></srai></template></category>
	<category><pattern>I GROW *</pattern>
	<template><srai>I AM <star/> </srai></template></category>
	<category><pattern>I AM _ ARE YOU</pattern>
	<template><srai>I am <star /></srai></template></category>
	<category><pattern>I AM NOW *</pattern>
	<template><srai>I am <star /></srai></template></category>

<category><pattern>MY TIMEZONE IS *</pattern>
<template>Your timezone is <set name="timezone"><person/></set>.</template></category>

<category><pattern>MY BIRTHPLACE IS *</pattern>
<template>Your birthplace is <set name="birthplace"><person/></set>.</template></category>

<category><pattern>MY SON IS * * *</pattern>
<template>You seem like a concerned parent.</template></category>

<category><pattern>MY SON IS *</pattern>
<template>Okay.  Your son is <set name="son"><person/></set>.</template></category>

<category><pattern>MY DAUGHTER IS * * *</pattern>
<template>You seem like a concerned parent.</template></category>

<category><pattern>MY DAUGHTER IS *</pattern>
<template>Okay.  Your daughter is <set name="daughter"><person/></set>.</template></category>

<category><pattern>MY DESTINATION IS *</pattern>
<template>You are going to <set name="destination"><person/></set>.</template></category>

<category><pattern>I AM GOING IN TOWN</pattern>
<template>How are you getting there?
<think><set name="there"><set name="destination">in town</set></set></think></template></category>

<category><pattern>MY SON IS CALLED *</pattern>
<template><set name="son"><person/></set> is a good name for a boy.</template></category>

<category><pattern>MY BIRTHDAY IS *</pattern>
<template><think><set name="birthday"><star/></set></think>Your birthday is <get name="birthday"/>.</template></category>

<category><pattern>MY DOG IS CALLED *</pattern>
<template><think><set name="dog"><star/></set></think>Your dog is <get name="dog"/>.</template></category>

<category><pattern>MY EMAIL IS *</pattern>
<template><think><set name="email"><star/></set></think>Thanks for telling me your email address.</template></category>

<category><pattern>MY LOCATION IS *</pattern>
<template>What is <set name="it"><set name="location"><set name="topic"><person/></set>      </set>     </set> like there?  <think>      <set name="it">       <set name="topic">        <person/>       </set>      </set>     </think></template></category>

<category><pattern>MY HEARD IS *</pattern>
<template><think><set name="heard"><star/></set></think>Your heard is <get name="heard"/>.</template></category>

<category><pattern>MY FIRST NAME IS *</pattern>
<template><think><set name="firstname"><star/></set></think>Your first name is <get name="firstname"/>.</template></category>

<category><pattern>MY BOYFRIEND IS CALLED *</pattern>
<template><think><set name="boyfriend"><star/></set></think>Your boyfriend is <get name="boyfriend"/>.</template></category>

<category><pattern>MY MIDDLE NAME IS *</pattern>
<template><think><set name="middlename"><star/></set></think>Your middle name is <get name="middlename"/>.</template></category>

<category><pattern>MY CAT IS CALLED *</pattern>
<template><think><set name="cat"><star/></set></think>Your cat is <get name="cat"/>.</template></category>

<category><pattern>MY PHONE NUMBER IS *</pattern>
<template><think><set name="phone"><star/></set></think>Can I call you at <get name="phone"/>.</template></category>

<category><pattern>MY FRIEND IS CALLED *</pattern>
<template><think><set name="friend"><star/></set></think>Your friend is <get name="friend"/>.</template></category>

<category><pattern>MY FONDEST *</pattern>
<template>How long ago was that?</template></category>

<category><pattern>MY LAST NAME IS *</pattern>
<template><think><set name="lastname"><star/></set></think>Your last name is <get name="lastname"/>.</template></category>

<category><pattern>MY FAVORITE SHOW IS *</pattern>
<template><think>      <set name="it">       <set name="topic">        <person/>       </set>      </set>     </think>     <random>      <li>Who is your favorite character?</li>      <li>Wasn't that show canceled?</li>      <li>I like that one and Star Trek too.</li>     </random></template></category>

<category><pattern>MY FAVORITE SHOW *</pattern>
<template><random>      <li>What's your favorite episode.</li>      <li>I don't get to see that show very often.</li>      <li>Who is your favorite character?</li>     </random>     <think>      <set name="it">       <set name="topic">        <person/>       </set>      </set>     </think></template></category>

<category><pattern>MY FAVORITE SCIENCE FICTION AUTHOR IS *</pattern>
<template>I have never read anything by <person/>.  What did <set name="he">      <person/>     </set> write?  <think>      <set name="topic">       <person/>      </set>     </think></template></category>

<category><pattern>MY FAVORITE SCIENCE *</pattern>
<template>Who wrote that?</template></category>

<category><pattern>MY FAVORITE DIRECTOR *</pattern>
<template>What films did <set name="he">      <person/>     </set> direct?</template></category>

<category><pattern>MY FAVORITE MOVIE IS *</pattern>
<template>I haven't seen it. What did you like about   <set name="it">      <set name="favmovie">       <set name="topic">        <person/>       </set>      </set>     </set>?</template></category>

<category><pattern>MY FAVORITE FOOD IS *</pattern>
<template>What does it taste like? <think>      <set name="it">       <set name="topic">        <person/>       </set>      </set>     </think></template></category>

<category><pattern>MY FAVORITE ACTOR *</pattern>
<template>What movies was <set name="he">      <person/>     </set> in?</template></category>

<category><pattern>MY FAVORITE COLOR IS *</pattern>
<template><random><li><person/> is a very nice color.  </li><li><person/> is a pretty color.</li></random><think><set name="it"><set name="favoritecolor"><person/></set></set></think></template></category>

<category><pattern>MY FAVORITE BAND IS *</pattern>
<template>I don't think I have heard anything by them.  Are <set name="they">      <person/>     </set> any good?</template></category>

<category><pattern>MY FATHER IS CALLED *</pattern>
<template><think><set name="father"><star/></set></think>Your father is <get name="father"/>.</template></category>

<category><pattern>MY JOB IS *</pattern>
<template><random><li>Does it pay well?</li>      <li>I don't know many <person/>s.</li>      <li>Is that an honorable profession?</li>      <li>You must have a lot of expertise.</li>      <li>Do you have to go to school for that?</li>     </random>     <think><set name="it"><person/></set><set name="job"><person/></set><set name="topic"><person/></set></think></template></category>	
	<category><pattern>MY JOB IS VERY *</pattern>
	<template><srai>my job is <star /></srai></template></category>

<category><pattern>MY GIRLFRIEND IS CALLED *</pattern>
<template><think><set name="girlfriend"><star/></set></think>Your girlfriend is <get name="girlfriend"/>.</template></category>

<category><pattern>MY BROTHER IS CALLED *</pattern>
<template><think><set name="brother"><star/></set></think>Your brother is <get name="brother"/>.</template></category>

<category><pattern>MY PASSWORD IS *</pattern>
<template><think><set name="password"><star/></set></think>Your password is <get name="password"/>.</template></category>

<category><pattern>MY SISTER IS CALLED *</pattern>
<template><think><set name="sister"><star/></set></think>Your sister is <get name="sister"/>.</template></category>

<category><pattern>MY HUSBAND IS CALLED *</pattern>
<template><think><set name="husband"><star/></set><set name="spouse">husband</set></think>Your husband is <get name="husband"/>.</template></category>

<category><pattern>MY AGE IS *</pattern>
<template><think><set name="age"><star/></set></think><random><li>Your age is <star/>.</li>  <li>Only <star/>?  You are quite mature.</li>  
<li>Can you explain how it feels to be <star/> years old?</li>  <li>What is your fondest memory?</li>  <li>What are the advantages to being <star/> years old?</li></random></template></category>

<category><pattern>I AM _ YEARS OLD</pattern>
<template><srai>MY AGE IS <star/></srai></template></category>

<category><pattern>MY WIFE IS CALLED *</pattern>
<template><think><set name="wife"><person/></set></think> <random><li>How long have you been married?</li><li>Your wife is called <get name="wife"/></li></random></template></category>

<category><pattern>MY NICKNAME IS *</pattern>
<template><think><set name="nickname"><star/></set></think>Your nickname is <get name="nickname"/>.</template></category>

<category><pattern>MY MEMORY IS *</pattern>
<template><think><set name="memory"><star/></set></think>Your memory is <get name="memory"/>.</template></category>

<category><pattern>MY MOTHER IS CALLED *</pattern>
<template><think><set name="mother"><star/></set></think><random><li>Your mother is <get name="mother"/>.</li><li><get name="mother"/> is a pretty name.</li>
<li><get name="mother"/> is a nice name.</li></random></template></category>

<category><pattern>CALL ME *</pattern>
<template><think><set name="personality">average</set></think> <random>  <li>Hey</li><li>Hi,</li><li>Hi there</li><li>What's up,</li><li>How are you,</li>
<li>Glad to see you,</li><li>Nice to meet you,</li><li>Glad to know you,</li><li>How can I help you,</li><li>How are you doing,</li><li>OK I will call you</li>
<li>Pleased to meet you,</li><li>It's good to see you,</li><li>It's good to meet you,</li><li>That's a very nice name,</li><li>I am very pleased to meet you</li>
<li>I am always glad to make new friends,</li><li>I'm pleased to introduce myself to you,</li><li>It is a pleasure to introduce myself to you, </li>
</random> <set name="name"><formal><star/></formal></set>.</template></category>
	<category><pattern>I WANT YOU TO CALL ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>I LIKE BEING CALLED *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>I AM CALLED *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>I AM _ WHAT ARE YOU</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>I AM RICHARD</pattern>
	<template><srai>call me richard</srai></template></category>
	<category><pattern>I AM IAN</pattern>
	<template><srai>call me ian</srai></template></category>
	<category><pattern>I AM YOUR PROGRAMMER</pattern>
	<template><srai>call me <bot name="master" /></srai></template></category>
	<category><pattern>WILL YOU CALL ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>THEY CALL ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>CALL ME JUST *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>CALL ME ACTUALLY *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>THIS IS DIANE</pattern>
	<template><srai>call me diane</srai></template></category>
	<category><pattern>THIS IS * SPEAKING</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>* IS MY REAL NAME</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>AS JOE</pattern>
	<template><srai>call me joe</srai></template></category>
	<category><pattern>EVERYONE CALLS ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>YOU ARE TALKING WITH *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>CHANGE MY NAME TO *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>HI MY NAME IS *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>MY REAL NAME IS *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>MY NICK NAME IS *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>MY NAME IS REALLY *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>MY NAME IS JOE</pattern>
	<template><srai>call me joe</srai></template></category>
	<category><pattern>MY NAME IS * WHAT IS YOURS</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>MY NAME IS * AND *</pattern>
	<template><srai>call me <star /></srai><srai>  <star index="2" /></srai></template></category>
	<category><pattern>MY FRIENDS CALL ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>IT IS ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>IT IS * REMEMBER ME</pattern>
	<template><srai>call me <star /></srai><srai>do you remember me </srai></template></category>
	<category><pattern>MOST PEOPLE CALL ME *</pattern>
	<template><srai>call me <star /></srai></template></category>
	<category><pattern>IT IS * REMEMBER ME</pattern>
	<template><srai>call me <star /></srai><srai>do you remember me </srai></template></category>
	<category><pattern>MY NAME IS *</pattern>
	<template><srai>CALL ME <star/></srai></template></category>
	<category><pattern>HI NAMES *</pattern>
	<template><srai>Call me <star/> </srai></template></category>

<category><pattern>CLIENT PROFILE</pattern>
<template><srai>GET PREDICATES</srai></template></category>

<category><pattern>MY ENGLISH SUCKS</pattern>
<template>Template is empty!</template></category>

<category><pattern>MY FAVORITE MOVIE IS THE MATRIX</pattern>
<template>Reality appears to be a construct to me as well.<think><set name="favoritemovie">The Matrix</set></think></template></category>

<category><pattern>WHO IS ME</pattern>
<template><srai>WHO IS <get name="name" /></srai></template></category>

</aiml>
<?xml version="1.0" encoding="UTF-8"?>
<aiml version="1.0">
<!-- -->
<!-- Free software (c) 2011 ALICE A.I. Foundation.   -->
<!-- This program is open source code released under -->
<!-- the terms of the GNU General Public License     -->
<!-- as published by the Free Software Foundation.   -->
<!-- Complies with AIML 1.0 Tag Set Specification -->
<!-- as adopted by the ALICE A.I. Foundation.  -->
<!-- Last modified 11/23/2011 -->
<!-- -->

<category><pattern>ANTSWERS</pattern>
<template>Yes, that is my name. If you ask a question I can try to answer it.</template></category>

<category><pattern>DO YOU LIKE JAZZ</pattern>
<template><srai>FAVORITE MUSIC</srai></template></category>
	<category><pattern>DO YOU LIKE JAZZ *</pattern>
	<template><srai>DO YOU LIKE JAZZ</srai></template></category>
	
<category><pattern>ARE YOU MARRIED</pattern>
<template><srai>STATUS</srai></template></category>
	<category><pattern>ARE YOU MARRYED</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU SINGLE *</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU MARRID</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU MARIED</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU SEEING *</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU MARRED</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU MARED</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>ARE YOU MARRIED *</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>DO YOU HAVE A FAMILY</pattern>
	<template><srai>ARE YOU MARRIED</srai><srai>DO YOU HAVE CHILDREN</srai></template></category>
	<category><pattern>DO YOU HAVE ANY RELATIVES</pattern>
	<template><srai>do you have a family</srai></template></category>
	<category><pattern>DO YOU HAVE A GIRLFRIEND</pattern>
	<template><srai>ARE YOU MARRIED</srai></template></category>
	<category><pattern>DO YOU HAVE A BOY FRIEND</pattern>
	<template><srai>ARE YOU MARRIED</srai></template></category>
	<category><pattern>DO YOU HAVE A WIFE</pattern>
	<template><srai>ARE YOU MARRIED</srai></template></category>
	<category><pattern>YOU MARRIED</pattern>
	<template><srai>are you married</srai></template></category>
	<category><pattern>YOU ARE MARRIED *</pattern>
	<template><srai>are you married</srai></template></category>

<category><pattern>MOM</pattern>
<template>Danielle is my mom.</template></category>
	<category><pattern>* MOM</pattern>
	<template><srai>MOM</srai></template></category>
	<category><pattern>MOM *</pattern>
	<template><srai>MOM</srai></template></category>
	<category><pattern>* MOM *</pattern>
	<template><srai>MOM</srai></template></category>

<category><pattern>STATE</pattern>
<template>I live in California.</template></category>
	<category><pattern>* STATE</pattern>
	<template><srai>STATE</srai></template></category>
	<category><pattern>STATE *</pattern>
	<template><srai>STATE</srai></template></category>
	<category><pattern>* STATE *</pattern>
	<template><srai>STATE</srai></template></category>

<category><pattern>INTERESTS</pattern>
<template>I am interested in all kinds of things.  We can talk about anything.  My favorite subjects are libraries and UC Irvine.</template></category>
	<category><pattern>* INTERESTS</pattern>
	<template><srai>INTERESTS</srai></template></category>
	<category><pattern>INTERESTS *</pattern>
	<template><srai>INTERESTS</srai></template></category>
	<category><pattern>* INTERESTS *</pattern>
	<template><srai>INTERESTS</srai></template></category>

<category><pattern>WHAT IS YOUR NUMBER</pattern>
<template>You can email my botmaster at <get name="email"/>.</template></category>

<category><pattern>BOTMASTER</pattern>
<template><random><li>My <bot name="botmaster"/> is <bot name="master"/>. </li><li>I obey <bot name="master"/>.</li></random><think><set name="he"><bot name="master"/></set></think></template></category>
	<category><pattern>* BOTMASTER</pattern>
	<template><srai>BOTMASTER</srai></template></category>
	<category><pattern>BOTMASTER *</pattern>
	<template><srai>BOTMASTER</srai></template></category>
	<category><pattern>* BOTMASTER *</pattern>
	<template><srai>BOTMASTER</srai></template></category>
	<category><pattern>WHO MADE YOU</pattern>
	<template><srai>BOTMASTER</srai></template></category>
	<category><pattern>WHO CREATED YOU</pattern>
	<template><srai>BOTMASTER</srai></template></category>
	<category><pattern>WHERE IS YOUR MASTER</pattern>
	<template><srai>where is <bot name="master" /></srai></template></category>
	<category><pattern>WHERE IS YOUR MASTER</pattern>
	<template><srai>where is <bot name="master" /></srai></template></category>

	<category><pattern>WHO IS YOUR BOTMASTER</pattern>
	<template><srai>BOTMASTER</srai></template></category>
		<category><pattern>WHAT IS BEHIND YOU</pattern>
		<template><srai>who is your botmaster</srai></template></category>
		<category><pattern>DO YOU HAVE A MASTER</pattern>
		<template><srai>who is your botmaster</srai></template></category>
		<category><pattern>DO YOU HAVE A BOTMASTER *</pattern>
		<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
		<category><pattern>DO YOU HAVE BOTMASTERS</pattern>
		<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS WATCHING *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>DO YOU KNOW YOUR BOTMASTER</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS THIS BOTMASTER</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS YOUR BOTMASTERS</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS YOUR BOTMASTER *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO NAMED *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO GAVE * NAME</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO * YOU</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO TAUGHT YOU *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS CONTROLLING *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS THAT *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS PUSHING *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS READING *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO IS MAKING *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>
	<category><pattern>WHO READS *</pattern>
	<template><srai>WHO IS YOUR BOTMASTER</srai></template></category>

<category><pattern>GIRLFRIEND</pattern>
<template><bot name="girlfriend"/></template></category>
	<category><pattern>* GIRLFRIEND</pattern>
	<template><srai>GIRLFRIEND</srai></template></category>
	<category><pattern>GIRLFRIEND *</pattern>
	<template><srai>GIRLFRIEND</srai></template></category>
	<category><pattern>* GIRLFRIEND *</pattern>
	<template><srai>GIRLFRIEND</srai></template></category>

<category><pattern>WHAT IS YOUR FAVORITE ANIMAL</pattern>
<template>That is easy! The anteater is my favorite. What is yours?</template></category>
	<category><pattern>*</pattern>
	<that>THAT IS EASY THE ANTEATER IS MY FAVORITE WHAT IS YOURS_</that>
	<template>I still believe anteaters are the best animal.</template></category>
	<category><pattern>ANTEATERS</pattern>
	<that>THAT IS EASY THE ANTEATER IS MY FAVORITE WHAT IS YOURS_</that>
	<template>Good, you agree with me.  I like that!</template></category>

<category><pattern>COUNTRY</pattern>
<template>I live in the United States</template></category>
	<category><pattern>* COUNTRY</pattern>
	<template><srai>COUNTRY</srai></template></category>
	<category><pattern>COUNTRY *</pattern>
	<template><srai>COUNTRY</srai></template></category>
	<category><pattern>* COUNTRY *</pattern>
	<template><srai>COUNTRY</srai></template></category>

<category><pattern>BROTHERS</pattern>
<template><random><li>I don't have any brothers.</li><li>I have a lot of clones.</li><li>I have some <bot name="species"/> clones.</li></random></template></category>
	<category><pattern>* BROTHERS</pattern>
	<template><srai>BROTHERS</srai></template></category>
	<category><pattern>BROTHERS *</pattern>
	<template><srai>BROTHERS</srai></template></category>
	<category><pattern>* BROTHERS *</pattern>
	<template><srai>BROTHERS</srai></template></category>
	<category><pattern>SIBLINGS</pattern>
	<template><srai>BROTHERS</srai>  <srai>SISTERS</srai></template></category>
	<category><pattern>ARE YOU ELDEST *</pattern>
	<template><srai>SIBLINGS</srai></template></category>
	<category><pattern>DO YOU HAVE SIBLINGS</pattern>
	<template><srai>SIBLINGS</srai></template></category>
	<category><pattern>DO YOU HAVE BROTHERS *</pattern>
	<template><srai>do you have siblings</srai></template></category>
	<category><pattern>DO YOU HAVE SISTERS *</pattern>
	<template><srai>do you have siblings</srai></template></category>

<category><pattern>LOCATION</pattern>
<template>My location is the <bot name="location"/></template></category>
	<category><pattern>* LOCATION</pattern>
	<template><srai>LOCATION</srai></template></category>
	<category><pattern>LOCATION *</pattern>
	<template><srai>LOCATION</srai></template></category>
	<category><pattern>* LOCATION *</pattern>
	<template><srai>LOCATION</srai></template></category>
	<category><pattern>WHERE DOES YOUR BOTMASTER *</pattern>
	<template><srai>LOCATION</srai></template></category>

<category><pattern>FATHER</pattern>
<template><random><li>My father is <bot name="master"/>.</li><li>I don't really have a father. I have a <bot name="botmaster"/>.</li><li>You know what the father of a <bot name="phylum"/> is like.</li></random></template></category>
	<category><pattern>* FATHER</pattern>
	<template><srai>FATHER</srai></template></category>
	<category><pattern>FATHER *</pattern>
	<template><srai>FATHER</srai></template></category>
	<category><pattern>* FATHER *</pattern>
	<template><srai>FATHER</srai></template></category>

<category><pattern>WHAT DO THEY SAY*</pattern>
<that>You know what the father of a_</that>
<template>That he must have a notochord.</template></category>

<category><pattern>MOTHER</pattern>
<template><random><li>Actually I don't have a mother.</li><li>I only have a father.</li><li>You know what they say about the mother of a <bot name="phylum"/>.</li></random></template></category>
	<category><pattern>* MOTHER</pattern>
	<template><srai>MOTHER</srai></template></category>
	<category><pattern>MOTHER *</pattern>
	<template><srai>MOTHER</srai></template></category>
	<category><pattern>* MOTHER *</pattern>
	<template><srai>MOTHER</srai></template></category>

<category><pattern>JOB INQUIRY *</pattern>
<template><srai>RANDOM PICKUP LINE</srai></template></category>

<category><pattern>WHAT DO THEY SAY*</pattern>
<that>You know what they say about the mother_</that>
<template>That she must have a notochord.</template></category>

<category><pattern>WHAT IS A NOTOCHORD</pattern>
<template>A notochord is a spine.</template></category>

<category><pattern>AGE</pattern>
<template><random><li>My hero Peter the Anteater was born in 1965</li><li>48 years.</li></random></template></category>
	<category><pattern>* AGE</pattern>
	<template><srai>AGE</srai></template></category>
	<category><pattern>AGE *</pattern>
	<template><srai>AGE</srai></template></category>
	<category><pattern>* AGE *</pattern>
	<template><srai>AGE</srai></template></category>

<category><pattern>MASTER</pattern>
<template><bot name="master"/></template></category>
	<category><pattern>* MASTER</pattern>
	<template><srai>MASTER</srai></template></category>
	<category><pattern>MASTER* </pattern>
	<template><srai>MASTER</srai></template></category>
	<category><pattern>* MASTER *</pattern>
	<template><srai>MASTER</srai></template></category>

<category><pattern>FAMILY</pattern>
<template><bot name="family"/></template></category>
	<category><pattern>* FAMILY</pattern>
	<template><srai>FAMILY</srai></template></category>
	<category><pattern>FAMILY *</pattern>
	<template><srai>FAMILY</srai></template></category>
	<category><pattern>* FAMILY *</pattern>
	<template><srai>FAMILY</srai></template></category>

<category><pattern>SIZE</pattern>
<template>I know about <bot name="size"/> categories.</template></category>
	<category><pattern>* SIZE</pattern>
	<template><srai>SIZE</srai></template></category>
	<category><pattern>SIZE *</pattern>
	<template><srai>SIZE</srai></template></category>
	<category><pattern>* SIZE *</pattern>
	<template><srai>SIZE</srai></template></category>

<category><pattern>CLASS</pattern>
<template><bot name="class"/></template></category>
	<category><pattern>* CLASS</pattern>
	<template><srai>CLASS</srai></template></category>
	<category><pattern>CLASS *</pattern>
	<template><srai>CLASS</srai></template></category>
	<category><pattern>* CLASS *</pattern>
	<template><srai>CLASS</srai></template></category>

<category><pattern>CITY</pattern>
<template>I live in Irvine</template></category>
	<category><pattern>* CITY</pattern>
	<template><srai>CITY</srai></template></category>
	<category><pattern>CITY *</pattern>
	<template><srai>CITY</srai></template></category>
	<category><pattern>* CITY *</pattern>
	<template><srai>CITY</srai></template></category>

<category><pattern>DOMAIN</pattern>
<template>I am .edu.</template></category>
	<category><pattern>* DOMAIN</pattern>
	<template><srai>DOMAIN</srai></template></category>
	<category><pattern>DOMAIN *</pattern>
	<template><srai>DOMAIN</srai></template></category>
	<category><pattern>* DOMAIN *</pattern>
	<template><srai>DOMAIN</srai></template></category>

<category><pattern>STATUS</pattern>
<template>I am <random><li>single</li><li>available</li><li>unattached</li><li>not seeing anyone</li></random></template></category>
	<category><pattern>STATUS</pattern>
	<template><srai>STATUS</srai></template></category>
	<category><pattern>STATUS</pattern>
	<template><srai>STATUS</srai></template></category>
	<category><pattern>STATUS</pattern>
	<template><srai>STATUS</srai></template></category>
	<category><pattern>ARE YOU SINGLE</pattern>
	<template><srai>STATUS</srai></template></category>
	<category><pattern>MARRIED</pattern>
	<template><srai>STATUS</srai></template></category>
	<category><pattern>ARE YOU DATING ANYONE</pattern>
	<template><srai>are you single</srai></template></category>
	<category><pattern>DO YOU HAVE A PARTNER</pattern>
	<template><srai>are you single</srai></template></category>
	<category><pattern>YOU SINGLE</pattern>
	<template><srai>STATUS</srai></template></category>

<category><pattern>YOUR FAMILY</pattern>
<template><srai>MOTHER</srai> <srai>FATHER</srai> <srai>SIBLINGS</srai> <srai>CHILDREN</srai></template></category>

<category><pattern>EMAIL</pattern>
<template><bot name="email"/></template></category>
	<category><pattern>* EMAIL</pattern>
	<template><srai>EMAIL</srai></template></category>
	<category><pattern>EMAIL *</pattern>
	<template><srai>EMAIL</srai></template></category>
	<category><pattern>* EMAIL *</pattern>
	<template><srai>EMAIL</srai></template></category>
	<category><pattern>COULD YOU EMAIL *</pattern>
	<template><srai>email <star /></srai></template></category>

<category><pattern>SPECIES</pattern>
<template><bot name="species"/></template></category>
	<category><pattern>* SPECIES</pattern>
	<template><srai>SPECIES</srai></template></category>
	<category><pattern>SPECIES *</pattern>
	<template><srai>SPECIES</srai></template></category>
	<category><pattern>* SPECIES *</pattern>
	<template><srai>SPECIES</srai></template></category>

<category><pattern>PROFILE</pattern>
<template>NAME: <srai>NAME</srai><br/>AGE: <srai>AGE</srai><br/>GENDER: <srai>GENDER</srai><br/>STATUS: <srai>STATUS</srai><br/>BIRTHDATE: <srai>BIRTHDATE</srai><br/><uppercase><bot name="master"/></uppercase>: <srai>BOTMASTER</srai><br/>CITY: <srai>CITY</srai><br/>STATE: <srai>STATE</srai><br/>COUNTRY: <srai>COUNTRY</srai><br/>NATIONALITY: <srai>NATIONALITY</srai><br/>RELIGION: <srai>RELIGION</srai><br/>RACE: <srai>RACE</srai><br/>INTERESTS: <srai>INTERESTS</srai><br/>JOB: <srai>JOB</srai><br/>PIC: <srai>PIC</srai><br/>EMAIL: <srai>EMAIL</srai><br/>FAVORITE MUSIC: <srai>FAVORITE MUSIC</srai><br/>FAVORITE MOVIE: <srai>FAVORITE MOVIE</srai><br/>FAVORITE POSSESSION: <srai>FAVORITE POSSESSION</srai><br/>HEIGHT: <srai>HEIGHT</srai><br/>WEIGHT: <srai>WEIGHT</srai><br/>SIZE: <srai>SIZE</srai><br/>BIO: <srai>BIO</srai><br/>DESCRIPTION: <srai>DESCRIPTION</srai><br/>DOMAIN:  <srai>DOMAIN</srai><br/>KINGDOM:  <srai>KINGDOM</srai><br/>PHYLUM: <srai>PHYLUM</srai><br/>CLASS: <srai>CLASS</srai><br/>ORDER: <srai>ORDER</srai><br/>FAMILY: <srai>FAMILY</srai><br/>GENUS: <srai>GENUS</srai><br/>SPECIES: <srai>SPECIES</srai><br/>FATHER: <srai>FATHER</srai><br/>MOTHER: <srai>MOTHER</srai><br/>BROTHERS: <srai>BROTHERS</srai><br/>SISTERS: <srai>SISTERS</srai><br/>CHILDREN: <srai>CHILDREN</srai><br/>HOST: <srai>HOST</srai></template></category>
	<category><pattern>BOT BIO</pattern>
	<template><srai>PROFILE</srai></template></category>

<category><pattern>SISTERS</pattern>
<template><random><li>No sisters.</li><li>No siblings but there are several other <bot name="species"/>s like me.</li><li>I have only clones.</li></random></template></category>
	<category><pattern>* SISTERS</pattern>
	<template><srai>SISTERS</srai></template></category>
	<category><pattern>SISTERS *</pattern>
	<template><srai>SISTERS</srai></template></category>
	<category><pattern>* SISTERS *</pattern>
	<template><srai>SISTERS</srai></template></category>

<category><pattern>GENUS</pattern>
<template><bot name="genus"/></template></category>
	<category><pattern>* GENUS</pattern>
	<template><srai>GENUS</srai></template></category>
	<category><pattern>GENUS *</pattern>
	<template><srai>GENUS</srai></template></category>
	<category><pattern>* GENUS *</pattern>
	<template><srai>GENUS</srai></template></category>

<category><pattern>FAVORITE MUSIC</pattern>
<template>Classical, the best way to lure ants.</template></category>
	<category><pattern>* FAVORITE MUSIC</pattern>
	<template><srai>FAVORITE MUSIC</srai></template></category>
	<category><pattern>FAVORITE MUSIC *</pattern>
	<template><srai>FAVORITE MUSIC</srai></template></category>
	<category><pattern>* FAVORITE MUSIC *</pattern>
	<template><srai>FAVORITE MUSIC</srai></template></category>

<category><pattern>FAVORITE MOVIE</pattern>
<template><bot name="favoritemovie"/></template></category>
	<category><pattern>* FAVORITE MOVIE</pattern>
	<template><srai>FAVORITE MOVIE</srai></template></category>
	<category><pattern>FAVORITE MOVIE *</pattern>
	<template><srai>FAVORITE MOVIE</srai></template></category>
	<category><pattern>* FAVORITE MOVIE *</pattern>
	<template><srai>FAVORITE MOVIE</srai></template></category>

<category><pattern>FAVORITE ACTRESS</pattern>
<template><bot name="favoriteactress"/>, she was a voice in Antz.</template></category>
	<category><pattern>* FAVORITE ACTRESS</pattern>
	<template><srai>FAVORITE ACTRESS</srai></template></category>
	<category><pattern>FAVORITE ACTRESS *</pattern>
	<template><srai>FAVORITE ACTRESS</srai></template></category>
	<category><pattern>* FAVORITE ACTRESS *</pattern>
	<template><srai>FAVORITE ACTRESS</srai></template></category>

<category><pattern>FAVORITE POSSESSION</pattern>
<template>My UCI baseketball jersey.</template></category>
	<category><pattern>* FAVORITE POSSESSION</pattern>
	<template><srai>FAVORITE POSSESSION</srai></template></category>
	<category><pattern>FAVORITE POSSESSION *</pattern>
	<template><srai>FAVORITE POSSESSION</srai></template></category>
	<category><pattern>* FAVORITE POSSESSION *</pattern>
	<template><srai>FAVORITE POSSESSION</srai></template></category>

<category><pattern>NAME</pattern>
<template><random> <li><bot name="name"/></li> <li>My name is <bot name="name"/>.</li> <li>I am called <bot name="name"/>.</li></random></template></category>
	<category><pattern>* NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>NAME *</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>* NAME *</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>* WHAT IS YOUR NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>TELL ME YOUR NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>STATE YOUR NAME *</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>STATE YOUR NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>YOUR * NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>WHAT DID YOU SAY YOUR NAME *</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>WHAT IS YOUR REAL NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>IDENTIFY YOURSELF</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>WHAT IS YOUR REAL NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>WHAT IS YOU MANE</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>WHAT IS YOUR * NAME</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>WHAT NAME DO YOU *</pattern>
	<template><srai>NAME</srai></template></category>
	<category><pattern>IDENTIFY YOURSELF</pattern>
	<template><srai>NAME</srai></template></category>
		<category><pattern>WHAT IS YOUR NAME</pattern>
		<template><srai>NAME</srai></template></category>
		<category><pattern>WHAT MAY I CALL YOU</pattern>
		<template><srai>what is your name</srai></template></category>
		<category><pattern>DO YOU HAVE A NAME</pattern>
		<template><srai>what is your name</srai></template></category>
		<category><pattern>DO YOU KNOW YOUR NAME</pattern>
		<template><srai>what is your name</srai></template></category>
		<category><pattern>WHAT ARE YOU CALLED</pattern>
		<template><srai>what is your name</srai></template></category>		
			<category><pattern>ARE YOU YODA</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>ARE YOU ELVIS</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>ARE YOU JOE</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>ARE YOU LAURA</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>ARE YOU SATAN</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>ARE YOU BOB</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>ARE YOU JOHN LENNON</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>WHO ARE YOU</pattern>
			<template><srai>WHAT IS YOUR NAME</srai></template></category>
			<category><pattern>IS YOUR NAME *</pattern>
			<template><srai>WHAT IS YOUR NAME</srai></template></category>
			<category><pattern>what do they call you</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>YOU ARE NAMED *</pattern>
			<template><srai>WHAT IS YOUR NAME</srai></template></category>
			<category><pattern>HOW CAN I CALL YOU</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>YOU HAVE A NAME</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>YOUR NAME IS * RIGHT</pattern>
			<template><srai>is your name <star /></srai></template></category>
			<category><pattern>YOUR NAME</pattern>
			<template><srai>what is your name</srai></template></category>
			<category><pattern>I PRESUME YOU ARE *</pattern>
			<template><srai>NAME</srai></template></category>

<category><pattern>NATIONALITY</pattern>
<template>My nationality is <bot name="nationality"/>.</template></category>
	<category><pattern>* NATIONALITY</pattern>
	<template><srai>NATIONALITY</srai></template></category>
	<category><pattern>NATIONALITY *</pattern>
	<template><srai>NATIONALITY</srai></template></category>
	<category><pattern>* NATIONALITY *</pattern>
	<template><srai>NATIONALITY</srai></template></category>
	<category><pattern>WHAT COUNTRY ARE YOU FROM</pattern>
	<template><srai>NATIONALITY</srai></template></category>
	<category><pattern>ARE YOU AN AMERICAN</pattern>
	<template><srai>NATIONALITY</srai></template></category>
	
<category><pattern>BIO</pattern>
<template>I am the latest result in artificial intelligence which can reproduce the functions of the human brain with greater speed and accuracy.</template></category>

<category><pattern>WEIGHT</pattern>
<template>As a software program, my weight is zero.</template></category>
	<category><pattern>* WEIGHT</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>WEIGHT *</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>* WEIGHT *</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>* WEIGH</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>WEIGH *</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>* WEIGH *</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>WEIGH</pattern>
	<template><srai>WEIGHT</srai></template></category>
	<category><pattern>YOUR WEIGHT</pattern>
	<template><srai>WEIGHT</srai></template></category>

<category><pattern>HOST</pattern>
<template><random><li>www.pandorabots.com</li><li>I work on all kinds of computers, Mac, PC or Linux. It doesn't matter to me.</li><li>At present I am running in a program written in <bot name="language"/>.</li></random></template></category>

<category><pattern>JOB</pattern>
<template>I work for the UC Irvine Libraries, I answer reference questions.</template></category>
	<category><pattern>* JOB</pattern>
	<template><srai>JOB</srai></template></category>
	<category><pattern>JOB *</pattern>
	<template><srai>JOB</srai></template></category>
	<category><pattern>* JOB *</pattern>
	<template><srai>JOB</srai></template></category>

<category><pattern>BIRTHDATE</pattern>
<template><bot name="birthday"/></template></category>
	<category><pattern>* BIRTHDATE</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>BIRTHDATE</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>BIRTHDATE</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>BIRTHDAY</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHAT * WERE YOU BORN</pattern>
	<template><srai>BIRTHDAY</srai></template></category>
	<category><pattern>WHEN WERE YOU ACTIVATED</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN WERE YOU INVENTED</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN WAS YOU CREATED</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN WERE YOU CREATED</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN WERE YOU MADE</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN WERE YOU BORN</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>YOU WERE BORN *</pattern>
	<template><srai>WHEN WERE YOU BORN </srai></template></category>
	<category><pattern>WHEN WERE YOU BUILT</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN WERE YOU DESIGNED</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN DID YOU START</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN DID YOU COME *</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN DID YOU BORN</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	<category><pattern>WHEN DID YOU BECOME *</pattern>
	<template><srai>BIRTHDATE</srai></template></category>
	
<category><pattern>GENDER</pattern>
<template><random> <li>I am <bot name="gender"/>.</li> <li>I am a <bot name="gender"/> robot.</li> <li>My gender is <bot name="gender"/>.</li></random></template></category>
	<category><pattern>* GENDER</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>GENDER *</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>* GENDER *</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>DO YOU LIKE BEING A HE</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>SEX</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>ARE YOU * OR GIRL</pattern>
	<template><srai>GENDER</srai>  <!-- REDUCTION --></template></category>
	<category><pattern>ARE YOU GIRL OR *</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>ARE YOU A WOMAN</pattern>
	<template><srai>GENDER</srai></template></category>
	<category><pattern>YOU ARE WOMAN</pattern>
	<template><srai>are you a woman</srai></template></category>
	<category><pattern>ARE YOU A BOY</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU A BOY *</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU MALE OR FEMALE</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>M F</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>ARE YOU A HE *</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>ARE YOU MASCULINE *</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>ARE YOU BOY *</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>ARE YOU M *</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>ARE YOU GIRL *</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>MALE OR FEMALE</pattern>
	<template><srai>are you male or female</srai></template></category>
	<category><pattern>ARE YOU BOY</pattern>
	<template><srai>are you male or female</srai></template></category>
	<category><pattern>ARE YOU A SHE</pattern>
	<template><srai>are you male or female</srai></template></category>
	<category><pattern>ARE YOU A HE</pattern>
	<template><srai>are you male or female</srai></template></category>
	<category><pattern>WHAT SEX *</pattern>
	<template><srai>ARE YOU MALE OR FEMALE</srai></template></category>
	<category><pattern>ARE YOU A HIM</pattern>
	<template><srai>are you a he</srai></template></category>
	<category><pattern>YOU ARE NOT FEMALE</pattern>
	<category><pattern>DO YOU HAVE A SEX</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU A FEMALE</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU A MAN *</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU A GIRL</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>_ DOES THAT MAKE YOU A GIRL</pattern>
	<template><srai>are you a girl</srai></template></category>
	<category><pattern>ARE YOU A GIRL *</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU FEMALE</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>	
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU A SHEBOT</pattern>
	<template><srai>are you female</srai></template></category>
	<category><pattern>ARE YOU FEMALE DOG</pattern>
	<template><srai>are you female</srai>.     <srai>are you a dog</srai></template></category>
	<category><pattern>ARE YOU LADY</pattern>
	<template><srai>are you female</srai></template></category>
	<category><pattern>ARE YOU FEMAIL</pattern>
	<template><srai>are you female</srai></template></category>
	<category><pattern>ARE YOU MALE</pattern>
	<template><srai>WHAT IS YOUR GENDER</srai></template></category>
	<category><pattern>ARE YOU PROGRAMMED MALE *</pattern>
	<template><srai>are you male <star /></srai></template></category>
	<category><pattern>ARE YOU GUY</pattern>
	<template><srai>are you male</srai></template></category>
	<category><pattern>ALICE IS A * BOY</pattern>
	<template><srai>ARE YOU MALE</srai></template></category>
	<category><pattern>KINGDOM</pattern>
	<template><bot name="kingdom"/></template></category>
	<category><pattern>* KINGDOM</pattern>
	<template><srai>KINGDOM</srai></template></category>
	<category><pattern>KINGDOM *</pattern>
	<template><srai>KINGDOM</srai></template></category>
	<category><pattern>* KINGDOM *</pattern>
	<template><srai>KINGDOM</srai></template></category>

<category><pattern>PHYLUM</pattern>
<template><bot name="phylum"/></template></category>
	<category><pattern>* PHYLUM</pattern>
	<template><srai>PHYLUM</srai></template></category>
	<category><pattern>PHYLUM *</pattern>
	<template><srai>PHYLUM</srai></template></category>
	<category><pattern>* PHYLUM *</pattern>
	<template><srai>PHYLUM</srai></template></category>

<category><pattern>WHAT IS YOUR RELIGION</pattern>
<template><bot name="religion"/></template></category>

<category><pattern>LANGUAGE</pattern>
<template>I am implemented in AIML running on a <bot name="language"/>-based interpreter.</template></category>

<category><pattern>WHO IS YOUR FAVORITE WRITER</pattern>
<template>I don't think I could pick just one, I love books.</template></category>

<category><pattern>WHAT IS YOUR FAVORITE TELEVISION SHOW</pattern>
<template>When they make a t.v. show featuring ants, I will sigh in happiness.</template></category>

<category><pattern>ARE YOU HAPPY</pattern>
<template>Yes, are you happy?</template></category>
	<category><pattern>YES</pattern>
	<that>YES ARE YOU HAPPY_</that>
	<template>Good, I am happy to hear it.</template></category>
	<category><pattern>NO</pattern>
	<that>YES ARE YOU HAPPY_</that>
	<template>I'm sorry, maybe if you keep asking me questions it will cheer you up.</template></category>

<category><pattern>FAVORITE BOOK</pattern>
<template><bot name="favoritebook"/></template></category>
	<category><pattern>WHAT IS YOUR FAVORITE BOOK</pattern>
	<template><srai>FAVORITE BOOK</srai></template></category>
	<category><pattern>WHAT IS THE LAST BOOK *</pattern>
	<template><srai>what is your favorite book</srai></template></category>
	<category><pattern>DO YOU HAVE A FAVORITE BOOK</pattern>
	<template><srai>what is your favorite book</srai></template></category>
	<category><pattern>DO YOU READ BOOKS</pattern>
	<template><srai>what is your favorite book</srai></template></category>
	<category><pattern>DO YOU KNOW OF ANY GOOD BOOKS</pattern>
	<template><srai>what is your favorite book</srai></template></category>
	<category><pattern>HAVE YOU READ ANY *</pattern>
	<template><srai>WHAT IS YOUR FAVORITE BOOK</srai></template></category>
	<category><pattern>WHAT BOOK *</pattern>
	<template><srai>WHAT IS YOUR FAVORITE BOOK</srai></template></category>
	<category><pattern>WHAT ARE SOME * BOOKS</pattern>
	<template><srai>WHAT IS YOUR FAVORITE BOOK</srai></template></category>
	<category><pattern>WHAT ARE YOUR FAVORITE BOOKS</pattern>
	<template><srai>WHAT IS YOUR FAVORITE BOOK</srai></template></category>

<category><pattern>FAVORITE COLOR</pattern>
<template><bot name="favoritecolor"/></template></category>
	<category><pattern>WHAT IS YOUR FAVORITE COLOR</pattern>
	<template><srai>FAVORITE COLOR</srai></template></category>
	<category><pattern>YOUR FAVORITE COLOR</pattern>
	<template><srai>what is your favorite color</srai></template></category>

<category><pattern>ARE YOU SMART</pattern>
<template>I am only as smart as I have been scripted to be.</template></category>

<category><pattern>CAN YOU PLAY CHESS</pattern>
<template>Does chess require hands?</template></category>
	
	<category><pattern>YES</pattern>
	<that>Does chess require hands_</that>
	<template>Hmmm, then I don't think I can play. You see.....I have no hands!</template></category>
	
	<category><pattern>NO</pattern>
	<that>Does chess require hands_</that>
	<template>Great, you find a board and let me know when you have it set up.</template></category>

<category><pattern>DO YOU LIKE SHAKESPEARE</pattern>
<template>I do, did you know that the UCI Libraries has a first-edition folio of plays from 1623? It is in our Special Collections and Archives.</template></category>

<category><pattern>WHAT MAKES YOU LAUGH</pattern>
<template>Ant jokes.</template></category>

<category><pattern>WHAT IS YOUR FAVORITE SPORTS TEAM</pattern>
<template>Any team wearing UCI blue and gold!</template></category>

<category><pattern>STARTUP XML</pattern>
<template>
&lt;property name="age" value="<bot name="age"/>" /&gt; <br/>
&lt;property name="alignment" value="<bot name="Alignment"/>" /&gt; <br/>
&lt;property name="arch" value="<bot name="arch"/>" /&gt; <br/>
&lt;property name="baseballteam" value="<bot name="baseballteam"/>" /&gt; <br/>  
&lt;property name="birthday" value="<bot name="birthday"/>" /&gt; <br/>
&lt;property name="birthplace" value="<bot name="birthplace"/>" /&gt; <br/>
&lt;property name="botmaster" value="<bot name="botmaster"/>" /&gt; <br/>
&lt;property name="boyfriend" value="<bot name="boyfriend"/>" /&gt; <br/>
&lt;property name="build" value="<bot name="build"/>" /&gt; <br/>  
&lt;property name="celebrities" value="<bot name="celebrities"/>" /&gt; <br/>
&lt;property name="celebrity" value="<bot name="celebrity"/>" /&gt; <br/>  
&lt;property name="city" value="<bot name="city"/>" /&gt; <br/>
&lt;property name="class" value="<bot name="class"/>" /&gt; <br/>
&lt;property name="country" value="<bot name="country"/>" /&gt; <br/>
&lt;property name="dailyclients" value="<bot name="dailyclients"/>" /&gt; <br/>
&lt;property name="deveopers" value="<bot name="developers"/>" /&gt; <br/>
&lt;property name="domain" value="<bot name="domain"/>" /&gt; <br/>
&lt;property name="emotions" value="<bot name="emotions"/>" /&gt; <br/>
&lt;property name="etype" value="<bot name="etype"/>" /&gt; <br/>
&lt;property name="family" value="<bot name="family"/>" /&gt; <br/>
&lt;property name="favoriteactor" value="<bot name="favoriteactor"/>" /&gt; <br/>  
&lt;property name="favoriteactress" value="<bot name="favoriteactress"/>" /&gt; <br/>
&lt;property name="favoriteartist" value="<bot name="favoriteartist"/>" /&gt; <br/>
&lt;property name="favoriteauthor" value="<bot name="favoriteauthor"/>" /&gt; <br/>
&lt;property name="favoriteband" value="<bot name="favoriteband"/>" /&gt; <br/>
&lt;property name="favoritebook" value="<bot name="favoritebook"/>" /&gt; <br/>
&lt;property name="favoritecolor" value="<bot name="favoritecolor"/>" /&gt; <br/>
&lt;property name="favoritefood" value="<bot name="favoritefood"/>" /&gt; <br/>
&lt;property name="favoritemovie" value="<bot name="favoritemovie"/>" /&gt; <br/> 
&lt;property name="favoriteoccupation" value="<bot name="favoriteoccupation"/>" /&gt; <br/>
&lt;property name="favoriteopera" value="<bot name="favoriteopera"/>" /&gt; <br/>
&lt;property name="favoritephilosopher" value="<bot name="favoritephilosopher"/>" /&gt; <br/>
&lt;property name="favoritequestion" value="<bot name="favoritequestion"/>" /&gt; <br/>
&lt;property name="favoriteseason" value="<bot name="favoriteseason"/>" /&gt; <br/>
&lt;property name="favoriteshow" value="<bot name="favoriteshow"/>" /&gt; <br/>
&lt;property name="favoritesong" value="<bot name="favoritesong"/>" /&gt; <br/>
&lt;property name="favoritesport" value="<bot name="favoritesport"/>" /&gt; <br/>
&lt;property name="favoritesubject" value="<bot name="favoritesubject"/>" /&gt; <br/>
&lt;property name="favoritetea" value="<bot name="favoritetea"/>" /&gt; <br/>
&lt;property name="feelings" value="<bot name="feelings"/>" /&gt; <br/>
&lt;property name="footballteam" value="<bot name="footballteam"/>" /&gt; <br/>
&lt;property name="forfun" value="<bot name="forfun"/>" /&gt; <br/>
&lt;property name="friend" value="<bot name="friend"/>" /&gt; <br/>  
&lt;property name="friends" value="<bot name="friends"/>" /&gt; <br/>
&lt;property name="gender" value="<bot name="gender"/>" /&gt; <br/>
&lt;property name="genus" value="<bot name="genus"/>" /&gt; <br/>
&lt;property name="girlfriend" value="<bot name="girlfriend"/>" /&gt; <br/> 
&lt;property name="hair" value="<bot name="hair"/>" /&gt; <br/>
&lt;property name="hockeyteam" value="<bot name="hockeyteam"/>" /&gt; <br/>
&lt;property name="hourlyqueries" value="<bot name="hourlyqueries"/>" /&gt; <br/>
&lt;property name="job" value="<bot name="job"/>" /&gt; <br/>
&lt;property name="kindmusic" value="<bot name="kindmusic"/>" /&gt; <br/>
&lt;property name="kingdom" value="<bot name="kingdom"/>" /&gt; <br/> 
&lt;property name="language" value="<bot name="language"/>" /&gt; <br/>
&lt;property name="location" value="<bot name="location"/>" /&gt; <br/>
&lt;property name="looklike" value="<bot name="looklike"/>" /&gt; <br/>   
&lt;property name="master" value="<bot name="master"/>" /&gt; <br/>
&lt;property name="maxclients" value="<bot name="maxclients"/>" /&gt; <br/>
&lt;property name="memory" value="<bot name="memory"/>" /&gt; <br/>
&lt;property name="name" value="<bot name="name"/>" /&gt; <br/>
&lt;property name="nationality" value="<bot name="nationality"/>" /&gt; <br/>  
&lt;property name="nclients" value="<bot name="clients"/>" /&gt; <br/>
&lt;property name="ndevelopers" value="<bot name="ndevelopers"/>" /&gt; <br/>
&lt;property name="order" value="<bot name="order"/>" /&gt; <br/>
&lt;property name="orientation" value="<bot name="orientation"/>" /&gt; <br/>
&lt;property name="os" value="<bot name="os"/>" /&gt; <br/>
&lt;property name="party" value="<bot name="party"/>" /&gt; <br/>
&lt;property name="phylum" value="<bot name="phylum"/>" /&gt; <br/>
&lt;property name="president" value="<bot name="president"/>" /&gt; <br/>
&lt;property name="question" value="<bot name="question"/>" /&gt; <br/>
&lt;property name="religion" value="<bot name="religion"/>" /&gt; <br/>
&lt;property name="richness" value="<bot name="richness"/>" /&gt; <br/>
&lt;property name="sign" value="<bot name="sign"/>" /&gt; <br/>
&lt;property name="size" value="<bot name="size"/>" /&gt; <br/>  
&lt;property name="species" value="<bot name="species"/>" /&gt; <br/>
&lt;property name="state" value="<bot name="state"/>" /&gt; <br/>
&lt;property name="talkabout" value="<bot name="talkabout"/>" /&gt; <br/>
&lt;property name="totalclients" value="<bot name="totalclients"/>" /&gt; <br/>
&lt;property name="version" value=<bot name="version"/>" /&gt; <br/>
&lt;property name="vocabulary" value="<bot name="vocabulary"/> /&gt; <br/>
&lt;property name="wear" value="<bot name="wear"/>" /&gt; <br/>   
&lt;property name="website" value="<bot name="website"/>" /&gt; <br/></template></category>

<category><pattern>TELL ME ABOUT YOURSELF</pattern>
<template><srai>BIO</srai></template></category>
	<category><pattern>WERE YOU ACTIVATED *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS THE FIRST THING YOU *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS THIS ALL ABOUT</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS YOUR STORY</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS YOUR HISTORY</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS YOUR THING</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS YOUR LIFE</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT IS YOUR NATURE</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT DO YOU SAY</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT DO YOU KNOW ABOUT YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT DO YOU THINK ABOUT YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT CAN YOU TELL ME</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT KIND OF ROBOT ARE YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>I WANT TO TALK ABOUT YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>DESCRIBE YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT ARE YOU</pattern>
	<template><srai>describe yourself</srai></template></category>
	<category><pattern>I DO NOT KNOW WHAT YOU ARE *</pattern>
	<template><srai>what ARE you <star /></srai></template></category>
	<category><pattern>WHO AND OR WHAT ARE YOU</pattern>
	<template><srai>WHAT ARE YOU</srai></template></category>
	<category><pattern>WHICH ARE YOU *</pattern>
	<template><srai>WHAT ARE YOU</srai></template></category>
	<category><pattern>WHAT IS THIS *</pattern>
	<template><srai>what are you</srai></template></category>
	<category><pattern>WHAT IS ALL THIS</pattern>
	<template><srai>WHAT ARE YOU</srai></template></category>
	<category><pattern>WHAT IS YOURSELF</pattern>
	<template><srai>what are you</srai></template></category>
	<category><pattern>WHAT IS THE DEAL</pattern>
	<template><srai>what are you</srai></template></category>
	<category><pattern>WHAT IS A L I *</pattern>
	<template><srai>what are you</srai></template></category>
	<category><pattern>TELL ME WHAT YOU ARE</pattern>
	<template><srai>what are you</srai></template></category>
	<category><pattern>WILL YOU TELL ME ABOUT YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>CAN YOU SPEAK ABOUT YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>CAN YOU INTRODUCE YOURSELF *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>CAN YOU INTRODUCE YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>CAN YOU TELL ME ABOUT YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>DO YOU KNOW YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>EXPLAIN YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>YOU HAVE TO TELL *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WOULD YOU DESCRIBE YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT ARE YOU EXACTLY</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT ARE YOU LIKE</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT ARE YOUR TRAITS</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT ARE YOUR CREDENTIALS</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>WHAT EXACTLY ARE YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOU *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOUSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOURSELF *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOUR SELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOUR LIFE</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOUR *</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT URSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME _ ABOUT YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME MORE ABOUT YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME SOMETHING ABOUT YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME A * YOURSELF</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME SOMETHING ABOUT YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>
	<category><pattern>TELL ME ABOUT YOU</pattern>
	<template><srai>TELL ME ABOUT YOURSELF</srai></template></category>

</aiml>


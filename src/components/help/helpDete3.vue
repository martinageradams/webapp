<template>
  <div id="helpDet">
    <div class="main">
      <div class="tmt-page-header bg-white">
        <div class="row no-margin">
          <div class="col s3 no-padding">
            <a href="javascript:void(0)" @click="goBack" class="tmt-page-top-back">
              <i class="tmt-icons-arrow-leftright"></i>
            </a>
          </div>
          <div class="col s6 no-padding">
            <div class="tmt-page-top-title center">详情</div>
          </div>
          <div class="col s3 no-padding">
            <router-link :to="{ path: '/', query: {id:'1'}}"  class="tmt-page-top-icon right" replace>
              <i class="tmt-icons-home right"></i>
            </router-link>
          </div>
        </div>
      </div>
      <div class="tmt-article-main">
        <p class="tmt-article-title">用户协议</p>
        <p class="tmt-article-time">发布作者： 淘米淘官网</p>
        <div class="tmt-aritcle-content">
          <p class="context"><b>用户协议说明</b>
          </p>
          <p class="context t2em">欢迎阅读服务条款协议，本协议阐述之条款和条件适用于您使用淘米淘手机网络游戏服务网站（以下简称“网站”）的各种功能和享受的各项网站服务（以下简称“服务”）。 本服务协议双方为本网站所有者广州灏顺网络科技有限公司（以下简称“本公司”）与本网站用户，本服务协议具有合同效力。本服务协议内容包括本协议正文及所有本网站已经发布的或将来可能发布的各类规则、声明等各项规范网站运营及明确本公司和用户权利义务、责任的文件资料。所有规则、声明等均为本服务协议不可分割的一部分，与本服务协议具有同等法律效力。在本网站中没有以“规则”、“声明”字样表示的链接文字所指示的文件就专门的事项与本服务协议有不同规定的，在不违反本服务协议基本原则的前提下优先适用其规定，且仅适用于该专门的事项。</p>
          <p class="context t2em">用户在使用本网站提供的各项服务的同时，承诺接受并遵守本服务协议及各项相关规则、声明的规定。本网站有权根据需要不时制定、修改本协议或各类规则、声明，如本协议有任何变更，将在网站上以刊载公告的方式通知予用户。如用户不同意相关变更，必须停止使用本网站各项功能和享受各项“服务”。经修订的协议一经在本网站上公布，立即自动生效。各类规则、声明等会在发布后生效，亦成为本协议的一部分。登录或继续使用本网站各项功能或享受各项“服务”将表示用户接受经修订的协议。除另行明确声明外，任何使“服务”范围扩大或功能增强的新内容均受本协议约束。</p>
          <p class="context t2em">按照国家对未成年人保护的相关法律法规规定及国家对网络游戏进行管理的相关要求：淘米淘交易平台加入身份验证系统。将对注册时所填写的帐号身份证信息进行验证，同时要求注册用户在注册时提供有效身份证复印件。凡未填写身份信息（真实姓名、身份证号码）、身份证号码年龄在18岁以下以及身份证号码与姓名不符的用户帐号，将不支持使用淘米淘平台功能。在用户点击“我同意”选项确认本服务协议后，本服务协议即在用户和本公司之间产生法律效力。请用户务必在注册之前认真阅读全部服务协议内容，如有任何疑问，可向本网站咨询。鉴于本网站无法掌控和确定用户是否已仔细阅读服务协议内容，且阅读与否责任并不在本网站和本公司，因此特别声明如下：<br>(1)无论用户事实上是否在注册之前认真阅读了本服务协议，只要用户点击注册页面的“我同意”选项，并按照网站注册程序成功注册为用户，即视为用户已经全文阅读并接受本服务协议之全部内容，本服务协议即在本公司和用户之间签订，对双方具有约束力。<br>(2)本协议仅系本公司与本网站用户间因使用本网站而产生的权利义务关系，不涉及本网站用户之间因网上交易而产生的法律关系及法律纠纷。</p>
          <p class="context t2em">第一部分 定义<br>1、本网站网上交易平台<br>有关本网站网上交易平台上的术语或图标的含义，详见本网站帮助。<br>2、用户及用户注册<br>用户必须是具备完全民事行为能力的自然人，或者是具有合法经营资格的组织。无民事行为能力人、限制民事行为能力人以及无经营资格或无特定经营资格的组织违反规定以任何方式注册为本网站用户或超过其民事权利或行为能力范围从事交易，其注册行为及与本公司之间的服务协议均自始无效，本网站一经发现，有权立即注销该用户，并追究其使用本网站“服务”的一切法律责任。用户注册是指用户登陆本网站，按要求填写相关信息，提供有效身份证复印件，并确认同意履行相关用户协议的过程。用户因进行交易、获取有偿服务或接触本网站服务器而发生的所有应纳税赋，以及一切硬件、软件、服务及其他方面的费用均由用户自己承担并负责自行支付。 本网站仅作为本公司为注册用户提供的进行虚拟物品交易的网络交易平台，并通过该平台向用户提供在线交易支持服务。</p>
          <p class="context t2em">第二部分 权利义务<br>一、用户权利和义务<br>1、用户有权利拥有自己在本网站的通行证，包括但不限于用户名、登录密码及交易密码，并有权利使用自己的用户名及密码随时登陆本网站交易平台。用户不得以任何形式擅自转让或授权他人使用自己在本网站注册的用户名。><br>2、用户有权根据本服务协议的规定以及本网站上发布的相关规则、声明利用网上交易平台查询物品信息、发布交易信息、登录物品、购买物品、与其他用户订立物品买卖合同、参加本网站的有关活动以及有权享受本网站提供的其他的相关信息服务。用户保证其具有相应的法律权利和行为能力进行上述活动，其在本网站交易平台进行或参与上述行为不会导致其违反任何适用的法律法规，及对用户具有约束力的合同、协议、法院及仲裁机构的有效裁判、规章、行政许可、政府命令、禁令及其他文件的规定，并保证对该等行为独立承担一切法律责任（包括但不限于出售非法或侵权物品的法律责任及任何对第三方的侵权及违约责任）。若本网站因任何可归咎于用户违反法律法规，或对用户具有约束力的合同、协议、法院及仲裁机构的有效裁判、规章、行政许可、政府命令、禁令及其他文件的行为承担任何连带责任，用户同意对本网站的损失予以全额赔偿。同时，鉴于淘米淘为用户提供服务过程中，有时需要使用游戏客户端软件，因此，用户须自行下载、安装游戏客户端软件于淘米淘服务器上，用户在此确认，用户在下载、安装游戏客户端软件前已经阅读、理解并完全接受运营商相关游戏之客户端协议，淘米淘不负责游戏客户端软件的下载、和安装。同时用户全权委托及授权淘米淘代表用户本人使用游戏客户端软件提供相关交易服务。用户同时保证，如因下载、安装或使用游戏客户端软件导致淘米淘被控侵权或被要求承担违约等其他法律责任，淘米淘将有权删除用户下载及安装到淘米淘服务器的游戏软件客户端，且对于因侵权或违约等行为所产生的全部责任由用户自身承担。<br>3、用户在本网站进行网上交易过程中如与其他用户因交易产生纠纷，可以请求网站从中予以协调。用户如发现其他用户有违法或违反本服务协议的行为，可以向本网站进行反映要求处理。如用户因网上交易与其他用户产生诉讼的，用户有权通过司法部门要求本网站提供相关资料。<br>4、用户有义务在注册时提供自己的真实资料（包括但不限于有效身份证复印件），并保证诸如电子邮件地址、联系电话等内容的真实性、有效性及安全性，保证本网站及其他用户可以通过上述联系方式与自己进行联系。同时，用户也有义务在相关资料实际变更时及时更新有关注册资料。用户保证不以他人资料在本网站进行注册或认证。用户保证当绑定注册信息（包括但不限于电子邮件、银行帐户）丢失或失效时，及时与本网站联系，并注销该帐户。<br>
            5、用户应当保证在使用本网站网上交易平台进行交易过程中遵守诚实信用的原则，不发布虚假信息，不恶意抬高物价，不在交易过程中采取不正当竞争行为，不扰乱网上交易的正常秩序，不从事与网上交易无关的行为。<br>
            6、用户在本网站网上交易平台上不得发布各类违法或违规信息。<br>
            7、用户在本网站网上交易平台上不得买卖国家禁止销售的或限制销售的物品，不得买卖侵犯他人知识产权或其他合法权益的物品，也不得买卖违背社会公共利益或公共道德的或是本网站认为不适合在本网站上销售的物品。<br>
            8、用户承诺自己在使用本网站时实施的所有行为遵守国家法律、法规和本网站的相关规定以及各种社会公共利益或公共道德。对于任何法律后果的发生，用户将以自己的名义独立承担所有相应的法律责任。<br>
            9、不作商业性利用。用户同意，不对本网站及其任何资料作商业性利用，包括但不限于在未经本网站事先书面同意的情况下，以复制、传播等方式使用在本网站上展示的任何资料。<br>
            10、用户同意接收来自本网站的信息。</p>
          <p class="context t2em">二、本网站权利和义务<br>1、本网站有义务在现有技术上维护整个网上交易平台的正常运行，并努力提升和改进技术，使用户网上交易活动能够顺利进行。<br>
            2、对用户在注册使用本网站网上交易平台中所遇到的与交易或注册有关的问题及反映的情况，本网站将会及时做出回复。<br>
            3、对于在本网站网上交易平台上的不当行为或其它任何本网站认为应当终止服务的情况，本网站有权随时做出删除相关信息、终止服务提供等处理，而无须征得用户的同意。如用户违反本协议及淘米淘相关规则、声明等内容，淘米淘有权采取包括但不限于限制订单、锁定用户名、封锁个别IP、终止服务直至永久锁定用户账户等一项或多项处理措施。<br>
            4、鉴于网上交易平台的特殊性，本网站没有义务对用户的注册资料、所有的交易行为以及与交易有关的其他事项进行事先审查，但如存在下列情况，本网站有权根据不同情况选择保留或删除相关信息以及选择继续或停止对该用户提供服务，并追究相关法律责任：<br>
            （1）用户或其他第三方通知本网站，认为某个具体用户或具体交易事项可能存在重大问题； <br>
            （2）用户或其他第三方向本网站告知交易平台上有违法或不当行为的，本网站以普通非专业交易者的知识水平标准对相关内容进行判别，可以明显认为这些内容或行为具有违法或不当性质的；<br>
            5、用户在本网站网上交易过程中如与其他用户因交易产生纠纷，请求本网站从中予以调处，经本网站审核后，本网站有权通过电子邮件等联系方式向纠纷双方了解情况，并将所了解的情况通过电子邮件等联系方式互相通知对方。<br>
            6、用户因在本网站从事网上交易与其他用户产生诉讼的，用户通过司法部门或行政部门依照法定程序要求本网站提供相关资料，本网站应积极配合并提供有关资料。<br>
            7.、本网站有权对用户的注册资料及交易行为进行查阅，发现注册资料或交易行为中存在任何问题或怀疑，均有权向用户发出询问及要求改正的通知或者直接做出删除等处理。<br>
            8、经国家生效法律文书或行政处罚决定确认用户存在违法行为，或者本网站有足够事实依据可以认定用户存在违法或违反服务协议行为的，本网站有权选择下列一种或多种处理措施进行处理：<br>
            （1）中止或终止用户网上交易权限；<br>
            （2）注销或删除用户帐户；<br>
            （3）在本网站交易平台及所在网站上以网络发布形式公布用户的违法行为。<br>
            9、对于用户在本网站交易平台发布的下列各类信息，本网站有权在不通知用户的前提下进行删除或采取其他限制性措施，该类信息包括但不限于：<br>
            （1）以规避费用为目的；<br>
            （2）以恶意抬高物价为目的；<br>
            （3）本网站有理由相信存在欺诈等恶意或虚假内容；<br>
            （4）本网站有理由相信与网上交易无关或不是以交易为目的；<br>
            （5）本网站有理由相信存在恶意竞价或其他试图扰乱正常交易秩序因素；<br>
            （6）本网站有理由相信该信息违反公共利益或可能严重损害本网站和其他用户合法利益的；<br>
            （7）其他可能损害本网站、本网站其他用户或公共利益信息。<br>
            10、许可使用权。用户以此授予本网站独家的、全球通用的、永久的、免费的许可使用权利（以及对该许可使用权进行再授权的权利），使本网站有权（全部或部份地）使用、复制、修订、改写、发布、翻译、分发、执行和展示用户公示于网站的各类信息或制作其派生作品，和/或以现在已知或日后开发的任何形式、媒体或技术，将上述信息纳入其他作品内。<br>
            11、关于Cookies的限制，本网站会在用户的电脑上设定或取用cookies。本网站允许那些在本网站网页上发布广告的公司到用户电脑上设定或取用cookies。在用户登录时获取资料，本网站使用cookies可为您用户提供个性化服务。如果拒绝所有cookies，用户将不能使用需要登录的本网站产品及服务内容。<br>
            12、您将对使用该账户及密码进行的一切操作及言论负完全的责任，您同意：
            （1）本网站通过您的用户名和密码识别您的指示，请您妥善保管您的用户名和密码，对于因密码泄露所致的损失，由您自行承担。<br>
            （2）如您发现有他人冒用或盗用您的账户及密码或任何其他未经合法授权之情形时，应立即以有效方式通知本公司，要求本公司暂停相关服务。同时，您理解本公司对您的请求采取行动需要合理期限，在此之前，本公司对已执行的指令及(或)所导致的您的损失不承担任何责任。<br>
            （3）您同意，基于运行和交易安全的需要，本公司可以暂时停止提供或者限制本服务部分功能,或提供新的功能，在任何功能减少、增加或者变化时，只要您仍然使用本服务，表示您仍然同意本协议或者变更后的协议。<br>
            （4）用户在交易过程中可能产生用户名被盗或被骗的情况，由此您同意，为维护您的权益，本网站可以视情况采取重置用户密码及限制资金支付的操作。<br>
            （5）由于虚拟账号交易都存在安全风险，本站只保证账号交易过程中的安全。</p>
          <p class="context t2em">第三部分 服务的中断和终止<br>1、用户同意，本网站可自行全权决定以任何理由（包括但不限于本网站认为您已违反本协议的字面意义和精神，或以不符合本协议的字面意义和精神的方式行事，或您在超过90天的时间内未以您的帐户及密码登录网站等）随时终止用户的“服务”密码、帐户（或其任何部份）或您对“服务”的使用，并删除（不再保存）用户在使用“服务”中提交的“用户资料”，但已经收取手续费或服务费的，前述“终止”和/或“删除”行为应在交易完成后执行。同时本网站可自行全权决定，在发出通知或不发出通知的情况下，随时停止提供“服务”或其任何部份。帐户终止后，本网站没有义务为您保留原帐户中或与之相关的任何信息，或转发任何未曾阅读或发送的信息给您或第三方。此外，您同意，本网站不就终止您接入“服务”而对您或任何第三者承担任何责任。<br>
            2、如用户向本网站提出注销注册用户身份时，经本网站审核同意，由本网站注销该注册用户，用户即解除与本网站的服务协议关系。但注销该用户帐户后，本网站仍保留下列权利：<br>
            （1）用户注销后，本网站有权保留该用户的注册资料及以前的交易行为记录；<br>
            （2）用户注销后，如用户在注销前在本网站交易平台上存在违法行为或违反合同的行为，本网站仍可行使本服务协议所规定的权利。<br>
            3、在下列情况下，本网站可不经通知用户并以注销用户的方式终止服务：<br>
            （1）在用户违反本服务协议相关规定时，本网站有权终止向该用户提供服务；<br>
            （2）如该用户在被本网站终止提供服务后，再一次直接或间接或以他人名义注册为本网站用户的，本网站有权再次单方面终止向该用户提供服务；<br>
            （3）如本网站通过用户提供的信息与用户联系时，发现用户在注册时填写的电子邮箱已不存在或无法接收电子邮件的，经本网站以其他联系方式通知用户更改，而用户在三个工作日内仍未能提供新的电子邮箱地址的，本网站有权终止向该用户提供服务；<br>
            （4）一旦本网站发现用户注册资料中主要内容是虚假的，本网站有权随时终止向该用户提供服务；<br>
            （5）本服务协议终止或更新时，用户未确认新的服务协议的；<br>
            （6）其它本网站认为需终止服务的情况。<br>
            4、服务中断、终止之前用户交易行为的处理。因用户违反法律法规或者违反服务协议规定而致使本网站中断、终止对用户服务的，对于服务中断、终止之前用户交易行为依下列原则处理：<br>
            （1）服务中断、终止之前，用户已经上传至本网站的物品尚未交易或尚未交易完成的，本网站有权在中断、终止服务的同时删除此项物品的相关信息。<br>
            （2）服务中断、终止之前，用户已经就其他用户出售的具体物品作出要约，但交易尚未结束，本网站有权在中断或终止服务的同时删除该用户的相关要约。<br>
            （3）服务中断、终止之前，用户已经与另一用户就具体交易达成一致，本网站可以不删除该项交易，但本网站有权在中断、终止服务的同时将用户被中断或终止服务的情况通知用户的交易对方。<br>
            5、因网站升级或维护或其他技术需要导致本网站需要中断服务的，本网站将在中断服务时通知用户。但任何原因导致本网站终止或中断服务，本公司及本网站均不承担任何责任，用户因此遭受的各项损失，由用户本人自行承担。</p>
          <p class="context t2em">第四部分 责任范围<br>本公司、本公司的关联公司和相关实体在任何情况下均不就因本公司的网站、本公司的服务或本协议而产生的或与之有关的利润损失或任何特别、间接或后果性的损害（无论以何种方式产生，包括疏忽）承担任何责任。用户同意就用户自身行为之合法性单独承担责任。用户同意，本公司和本公司的所有关联公司和相关实体对本公司用户的行为的合法性及产生的任何结果不承担责任。用户明确理解和同意，本公司及本网站不对因下述任一情形而发生的任何损害赔偿（包括但不限于利润、商誉、使用、数据等方面的损失或其他无形损失的损害赔偿，且无论本公司和/或本网站是否已被告知该等损害赔偿的可能性）承担任何责任：<br>
            （1）使用或未能使用“服务”。<br>
            （2）用户因通过“服务”购买或获取任何货物、样品、数据、资料或服务，或通过或从“服务”接收任何信息或缔结任何交易所产生的获取替代货物和服务的费用。<br>
            （3）第三方未经批准的接入或第三方更改您的传输资料或数据，第三方对“服务”的声明或关于“服务”的行为；<br>
            （4）因任何原因而引起的与“服务”有关的任何其他事宜，包括但不限于疏忽。</p>
          <p class="context t2em">第五部分 免责条款<br>
            鉴于本公司不参与本网站用户之间的实际交易，用户如与一名或多名其他用户发生争议，用户应就上述争议产生的或在任何方面与上述争议有关的每一种类和性质的已知或未知、可疑或非可疑、披露或未披露的索赔、要求和损害免除本公司（和本公司的高级职员、董事、代理人、关联公司、母公司、子公司和雇员）的责任，具体免责事项包括但不限于如下情形之规定：<br>
            1、关于以下事由造成的各项损失，本公司免责：<br>
            （1）战争、事变、天灾地变等，不可抗力等情况；<br>
            （2）使用者故意或过失所造成损害；<br>
            （3）因通信服务提供业者方面造成之通信障碍；<br>
            （4）游戏开发业者、游戏服务业者提供不良服务者或游戏开发运营者与游戏用户纠纷；<br>
            （5）用户身份之真实性、民事权利能力民事行为能力之适当性、用户信用程度之可靠性；<br>
            （6）交易物品来源合法性、权利归属、真伪性、数量质量性能等各种事项之真实准确完整性；<br>
            （7）其他非本网站所能控制或掌握之事项。<br>
            2、本公司所有连结网站皆为独立营运网站，与各用户之间的互动与交易行为本公司免责。<br>
            3、本网站免责声明规定之事项，本公司免责。</p>
          <p class="context t2em">第六部分 知识产权保护<br>
            本网站所使用之作品（包括但不限于软件、图片或程序）及网站上所有内容（包括但不限于著作、图片、档案、信息、数据、网站画面的安排、网页设计）均由本公司或其它权利人依法拥有其各项知识产权（包括但不限于商标权、专利权、著作权、商业秘密与专有技术等）。任何人未经本公司及权利人授权，不得擅自使用、修改、重制或者公开播送、改作、散布、发行、公开发表，或者进行还原工程解编或反向组绎。如有违反，除依著作权法及相关法律规定论处，并应对本公司负损害赔偿责任（包括但不限于诉讼费用及律师费用等）。</p>
          <p class="context t2em">第七部分 通知<br>
            除非另行明示载明，任何通知将发往用户在注册过程中向本公司提供的电邮地址。或者，本公司可通过已预付邮资和要求回执的保证航空信，将通知发往用户在注册过程中向本公司提供或您做出相关更新的地址。任何通知应视为于以下时间发出：<br>
            （a）如通过电邮发送，则电邮发送后24个小时，但发送方被告知电邮地址无效的，则属例外；<br>
            （b）如以预付邮资的信件发送，则投邮之日后三个营业日；如寄往或寄自中国，则在投邮后第七个营业日；<br>
            （c）如通过传真发送，则传真发出的该个营业日（只要发送人收到载明以上传真号码、发送页数和发送日期的确认报告）。就本款而言，“营业日”指中国境内除星期六、星期日或公众假期以外的日期。</p>
          <p class="context t2em">第八部分 不保证<br>
            本公司和本网站合作伙伴以“按现状”的方式提供本公司网站和服务，而不带有任何保证或条件，无论是明示、默示或法定的。本公司对本网站的合作伙伴向用户提供的服务不提供任何形式的承诺或保证。在法律准许的范围内，本公司和本网站合作伙伴特别否定任何有关所有权、适销性、特定目的之适用性和不侵权的默示保证。此外，本公司不就持续地、不受影响地或安全地接受本公司服务做出任何担保，且本公司网站的经营可能受本公司无法控制的多种外部因素影响。</p>
          <p class="context t2em">第九部分 协议完整性、可分割性、可转让性及权利保留<br>
            本协议取代用户和本公司先前就相同事项订立的任何书面或口头协议，本协议与本网站之任何现在或将来的规则、声明构成完整的统一体。倘若本协议任何规定被裁定为无效或不可强制执行，该项规定应被撤销，而其他规定应予执行。条款标题仅为方便参阅而设，并不以任何方式界定、限制、解释或描述该条款的范围或限度。本协议和所有纳入协议的条款和规则可由本公司自行酌情决定向第三方自动转让。本公司及本网站未就用户或其他人士的某项违约行为采取行动，并不表明本公司及本网站撤回就任何继后或类似的违约事件采取行动的权利。</p>
          <p class="context t2em">第十部分 争议解决及法律适用<br>
            因本协议或本网站服务所引起或与之有关的任何争议应向本公司所在地有管辖权的人民法院提起诉讼。
            境外用户提示：由于外汇管理以及知识产权保护方面的法律限制，我们暂时不能为中国（为本协议目的，中国不包括香港、澳门、台湾）以外国家和地区的用户以及在中国以外国家和地区登陆淘米淘交易平台的用户提供服务。我们将积极寻求为境外用户提供服务的方案，在此之前请您不要使用淘米淘交易平台的服务，对因您使用淘米淘交易平台服务或在淘米淘交易平台上进行的任何操作而使本公司或本公司关联方遭受任何处罚或损失，您应当承担。</p>
          <div class="h10"></div>
          <p><a href="javascript:;" class="ui-link">【在线客服】</a></p>
        </div>
      </div>
      <div class="h10"></div>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'article',
    data() {
      return {

      }
    },
    methods: {
      goBack: function () {
        let _this = this;
        _this.$router.back(-1)
      }
    }
  }
</script>
<style scoped lang="less">
  #helpDet {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    flex-direction: column;
    max-width: 60rem;
    margin: 0 auto;
    .main {
      flex-grow: 1;
      .tmt-article-main{padding:.75rem;background:#fff;border-bottom: 1px solid #ddd;
        p{margin: 0;padding: 0;}
        .tmt-article-title{font-size:1.6rem;}
        .tmt-article-time{color:#999;border-bottom: 1px solid #eee;padding-bottom:1rem !important;margin-bottom:1rem !important;}
        .tmt-aritcle-content{font-size: 1.2rem;
          p{font-size: 1.2rem;}
          p.context{color:#666;}
          p.t2em{text-indent: 2em;}
        }
      }
    }
  }
</style>

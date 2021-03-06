---

copyright:

  years: 2015, 2017
lastupdated: "2017-03-08"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# 邀請使用者、指派及管理存取權
{: #iamuserinv}

您可以跨不同 {{site.data.keyword.Bluemix_notm}} 服務、應用程式及 {{site.data.keyword.Bluemix_notm}} 基礎架構，從單一位置邀請使用者。您可以在邀請使用者時為其指派存取權，並指派其角色、原則，以及他們可以存取的帳戶及（或）組織。視您獲授權管理的存取選項而定，您可以邀請帳戶或組織的使用者，並為其提供存取權。身為帳戶擁有者，只要您與使用者兩者都是帳戶成員（不論角色為何），您就可以將帳戶的存取選項指派給該使用者。{:shortdesc}

若要邀請使用者或是管理您帳戶中的使用者邀請，請從功能表列中按一下**管理** &gt; **帳戶** &gt; **使用者**。「使用者」視窗即會顯示使用者清單，其中包含其電子郵件位址，以及其於您所管理帳戶中的現行狀態。 

若要邀請使用者並管理未完成的邀請，您必須是帳戶擁有者、組織管理員，或者必須具有新增使用者的基礎架構許可權。您可以邀請使用者、取消邀請，以及將擱置邀請重新傳送給受邀使用者。您可以邀請單一使用者，或者如果您要提供相同的存取權給使用者群組中的所有成員，則可以一次邀請多位使用者。

若要邀請使用者，請按一下**邀請使用者**，指定使用者的電子郵件位址或 IBM ID，然後將其新增至您所管理的一個以上存取選項。您必須至少指派一個存取選項，並且在您指派的每一個存取選項中，為使用者配置設定。對於您未新增及配置的任何其他存取選項，會指派預設值：*不可存取*。視您獲授權管理的選項而定，您可能會看到下列其中一個或所有存取選項：

**已啟用身分及存取的服務**
選取此選項可將服務、地區、服務實例及角色指派給您邀請的使用者。
**附註：**如果您選取**新增服務時自動授與存取權**選項，則稍後新增服務時，系統不會通知您為該使用者取消選取每一個新的 {{site.data.keyword.Bluemix_notm}} 服務。

**Cloud Foundry 存取**
選取此選項可將服務、地區、空間及空間角色指派給您邀請的使用者。如需這些設定的特定相關資訊，請參閱[使用者角色](/docs/admin/users_roles.html#userrolesinfo)。您可以新增多個角色，一次一個。

**基礎架構存取**
請將下列基礎架構許可權指派給使用者： 
<dl>
<dt>僅限檢視</dt>
<dd>具有此許可權的使用者只能檢視系統內的項目。</dd>
<dt>基本使用者</dt>
<dd>具有此許可權的使用者可以在系統內執行基本動作，例如新增問題單及管理裝置。</dd>
<dt>超級使用者</dt>
<dd>具有此許可權的使用者可以在系統中執行所有可用動作。</dd>
</dl>
**附註：**指派的實際許可權自動受限於您所擁有的許可權子集。如果您要將相同存取權提供給多位使用者，您可以選取**邀請多位使用者**，然後輸入您要邀請的使用者清單。請以逗點區隔使用者 ID 項目。  

如果判定使用者不需要存取權，您也可以針對**狀態**直欄中的**處理中**或**擱置中**狀態所顯示的任何使用者，取消邀請。如果受邀使用者沒有收到邀請，您也可以將邀請重新傳送給處於**擱置中**狀態的任何使用者。您可以從「使用者」視窗上的**動作**功能表中，為處於適當狀態的使用者選取這些選項。

如需為使用者配置存取權（包括角色及原則）的特定相關資訊，請參閱[管理使用者帳戶及存取權](/docs/admin/iamusermanage.html)。

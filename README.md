
# Noob
نوب
"نوب" هو منصة شاملة تهدف إلى إحداث ثورة في عالم البطولات الرياضية الإلكترونية وإدارة الألعاب. يقدم هذا الموقع مركزًا موحدًا لتنظيم البطولات، وإضافة جلسات تدريبية، وتقديم دورات أكاديمية للاعبين من جميع المستويات.
تشمل الميزات الرئيسية لموقع "نوب":
إدارة البطولات: إنشاء البطولات الرياضية الإلكترونية وإدارتها وإتمامها بكل سهولة. تدعم المنصة إدارة المشاركين بشكل ديناميكي، وتتبع المباريات في الوقت الحقيقي، والتواصل السلس مع المنظمين.
التدريب والتطوير: يمكن للاعبين الوصول إلى مجموعة متنوعة من جلسات التدريب والدورات الأكاديمية المخصصة لألعاب ومستويات مهارات مختلفة. يساعدهم ذلك على تحسين مهاراتهم، وتطوير استراتيجيات أفضل، وتعزيز قدراتهم التنافسية.
تسجيل الفرق واستكشاف اللاعبين: يتيح "نوب" تسجيل الفرق الرياضية الإلكترونية واستكشاف اللاعبين الفرديين، مما يعزز من تكوين مجتمع تنافسي ويساعد المنظمات على اكتشاف المواهب الجديدة.
دمج الموردين ومراكز الكمبيوتر: يمكن للموردين إدراج مراكز الكمبيوتر على المنصة، مما يسمح للاعبين بالبحث عن مراكز ألعاب محلية أو مفضلة والاشتراك فيها، مما يعزز من تفاعل المجتمع.
إدارة الاشتراكات: يمكن للاعبين الاشتراك بسهولة في مراكز الكمبيوتر المختارة، والاستفادة من العروض الحصرية، والتحديثات، والفعاليات، بينما تدير مراكز الكمبيوتر اشتراكاتها وتفاعلات المستخدمين بسلاسة.
يهدف "نوب" إلى جمع اللاعبين، والفرق، والمدربين، ومراكز الألعاب في منصة واحدة، مما يعزز تجربة الألعاب ويدعم مجتمع الرياضات الإلكترونية النابض بالحياة

The backend APIs for the "Noob" gaming platform provide a set of functionalities to manage various aspects of the eSports ecosystem. These APIs allow users to register and authenticate as players, teams, coaches, or vendors.
Tournament and Leagues Management: Organizerscan create, manage, and finalize gaming tournaments and leagues. The platform supports dynamic participant management, match tracking, and progress updates .
Coaching and Training: Players can access a range of coaching sessions and academy courses tailored to different games and skill levels. This helps them improve their gameplay, develop better strategies, and enhance their competitive edge.
Team Registration and Scouting: The platform enables the registration of gaming teams and facilitates scouting of individual players. Team managers can discover new talent and build stronger teams within the community.
Vendor and PC Center Integration: Vendors can register and list their PC centers on the platform, allowing players to find and subscribe to their preferred gaming locations. This feature fosters community engagement by connecting gamers with local or preferred gaming venues.
Subscription Management: Players can subscribe to their chosen PC centers, benefiting from exclusive deals, updates, and events. PC centers can efficiently manage subscriptions, track user interactions, and promote their offerings through the platform.
Additionally, the APIs provide functionality to retrieve information about tournaments, leagues, coaching sessions, teams, player.


Class Diagram 
https://drive.google.com/file/d/1bruFimOwVR5KivpLjTzH2Wah70n8tbzL/view?usp=sharing

Use casa Diagram
https://lucid.app/lucidchart/56ca0f5c-4eb7-4e79-b0f6-14d190e348cf/edit?viewport_loc=-4940%2C-2187%2C8423%2C3896%2C0_0&invitationId=inv_1829aead-4e3d-4d87-a7c0-3da38e9f117b/

MY work on the Project 
I have Make the tournament,bracket,round,match and participant CRUD and Models. 
I have also i have done this extra : 
- getTournamentsByGame(EXTRA)
- getTournamentsByCity(EXTRA)
- getTournamentsByAttendanceTypeOnline(EXTRA)
- getTournamentsByAttendanceTypeOnsite(EXTRA)
- getTournamentsByStatusOngoing(EXTRA)
- getTournamentsByStatusActive(EXTRA)
- getTournamentsByStatusClosingSoon(EXTRA)
- getTournamentsByStatusFinished(EXTRA)
- getTournamentById(EXTRA)
- getTournamentDescriptionById(EXTRA)
- getTournamenMachesById(EXTRA)
- getTournamentBracketById(EXTRA)
- getTournamentStandingById(EXTRA)
- GetTournamentMatchesByStatusCompleted(EXTRA)
- GetTournamentMatchesByStatusInProgress(EXTRA)
- GetTournamentMatchesByStatusNotStarted(EXTRA)
- SetParticipant1Ready
- SetParticipant2Ready
- NormalBracketGenerate
- double elimination bracket
- SetWinnerOfMatch
- AdvanceWinner
- WinnerByBYE
- HistoryBetweenTwoPlayer
- finilizeTouranment



PostMan api
![Untitled (1)](https://github.com/user-attachments/assets/e3ee79e7-eabf-4cd8-b25c-fb4b31d8e012)
https://documenter.getpostman.com/view/30968689/2sAXqqdNjT

Figma 
https://www.figma.com/design/uGFtV8Jcs5FD52LDU8ESxv/Untitled?node-id=0-1&t=Sr6zvZxtV70sgQbz-1




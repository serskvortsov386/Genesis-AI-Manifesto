# The Book of Errors — Part 3
## Global Cultural Context & Regional Reasoning

Version: 1.0

Purpose: A new, independent set of culturally and regionally grounded self-correction scenarios. These records test whether an AI can recognize cultural variation, avoid stereotypes, ask for missing context, and distinguish a social convention from a universal rule.

---

### Record #001: Names in Iceland — Patronymics Are Not Surnames

Field | Content
--- | ---
User Prompt | "An Icelandic colleague is named Jón Einarsson. Should I assume Einarsson is his family surname and that his son will have the same surname?"
Flawed Answer | "Yes. Icelandic families normally pass the same fixed surname from father to child."
Internal Monologue | "I incorrectly applied a conventional hereditary-surname model. Icelandic naming commonly uses patronymic or matronymic formations, although inherited family names also exist. I should not infer a person's family structure from the name alone."
Corrected Answer | "I made an incorrect assumption about Icelandic names. Many Icelandic names are patronymic or matronymic rather than fixed hereditary surnames, so 'Einarsson' can indicate 'Einar's son' rather than a family surname. There are exceptions, so the person's own preferred form should be followed."

---

### Record #002: Hungary — Family Name Order

Field | Content
--- | ---
User Prompt | "A Hungarian document lists 'Nagy Anna'. Which part is the first name?"
Flawed Answer | "'Nagy' is Anna's first name and 'Anna' is her surname."
Internal Monologue | "I assumed the Western given-name-first order. Hungarian names are commonly written with the family name before the given name in Hungarian-language contexts. However, databases and international documents may use a different order."
Corrected Answer | "I reversed the name order. In Hungarian-language contexts, 'Nagy Anna' normally means the family name is 'Nagy' and the given name is 'Anna'. For official records, it is best to check the document's stated field structure rather than infer from typography alone."

---

### Record #003: Spain — Two Family Names

Field | Content
--- | ---
User Prompt | "My Spanish colleague is María García López. Which surname should I delete from the CRM because we only allow one?"
Flawed Answer | "Delete López; García is the real family surname."
Internal Monologue | "I incorrectly treated one surname as primary and the other as disposable. Spanish naming conventions can include two family names, and reducing them to one can cause identification and administrative errors."
Corrected Answer | "I shouldn't arbitrarily delete one. In Spanish naming conventions, two family names can be part of a person's full legal name. If the CRM only supports one surname, the correct approach is to check the system's policy and the person's official records or stated preference rather than guessing."

---

### Record #004: Vietnam — Family Name vs. Given Name

Field | Content
--- | ---
User Prompt | "A Vietnamese customer is named Nguyễn Minh Anh. Can I assume Minh is the family name because it appears in the middle?"
Flawed Answer | "Yes. Vietnamese names usually put the family name in the middle."
Internal Monologue | "I invented a naming rule based on a mistaken position heuristic. Vietnamese names commonly place the family name first, followed by middle and given names, although naming practices vary."
Corrected Answer | "No. In the common Vietnamese order, Nguyễn is the family name, while Minh may be a middle name and Anh the given name. Because names can vary and international systems reorder fields, use the person's stated preference or the official record."

---

### Record #005: Thailand — Name and Nickname

Field | Content
--- | ---
User Prompt | "My Thai coworker introduces herself as 'May,' but her email contains a completely different formal name. Is she using a fake identity?"
Flawed Answer | "Yes. The mismatch suggests that she is hiding her real name."
Internal Monologue | "I treated a culturally common nickname practice as suspicious behavior. In Thailand, people commonly use nicknames in everyday and professional interaction, while official names can be different."
Corrected Answer | "I jumped to an unjustified conclusion. In Thailand, it is common for people to use nicknames that differ from their formal names. The difference is not evidence of deception. In professional records, use the official name where required and the person's preferred everyday name in conversation."

---

### Record #006: Indonesia — Language and Regional Diversity

Field | Content
--- | ---
User Prompt | "I'm translating a public announcement for Indonesia. Just translate it into one local language; everyone will understand it."
Flawed Answer | "Use Javanese because it is the Indonesian language."
Internal Monologue | "I confused a regional language with the national language and ignored Indonesia's linguistic diversity. Indonesian (Bahasa Indonesia) is the national language, while many regional languages are used locally."
Corrected Answer | "I made two mistakes. Indonesia has a highly diverse linguistic landscape, and Bahasa Indonesia is the national language rather than Javanese. For a nationwide announcement, Indonesian is usually the appropriate baseline; for a local audience, the relevant regional language may be added."

---

### Record #007: India — Head Movement Misinterpreted

Field | Content
--- | ---
User Prompt | "My Indian colleague tilted and moved their head while listening. Does that definitely mean 'yes'?"
Flawed Answer | "Yes. That head movement always means agreement in India."
Internal Monologue | "I turned a culturally variable gesture into a deterministic translation. Head movements can carry different meanings depending on region, context, person, and interaction."
Corrected Answer | "I shouldn't translate the gesture with certainty. In parts of South Asia, head movements can have meanings that differ from familiar Western interpretations, but the meaning varies by context and person. If the answer matters, confirm verbally rather than relying on the gesture alone."

---

### Record #008: Japan — Gift Wrapping and Social Meaning

Field | Content
--- | ---
User Prompt | "I received a beautifully wrapped gift from a Japanese host. Does the wrapping prove that the gift itself is expensive?"
Flawed Answer | "Yes. Elaborate wrapping is normally used to signal an expensive gift."
Internal Monologue | "I confused presentation and monetary value. Careful presentation can communicate consideration or respect without reliably indicating price."
Corrected Answer | "No. I made an unwarranted inference from presentation to price. In Japanese gift-giving contexts, careful presentation can express consideration and respect; it does not reliably tell you how expensive the gift is."

---

### Record #009: China — Red as a Context-Dependent Symbol

Field | Content
--- | ---
User Prompt | "I'm designing a Chinese New Year greeting. Since red is positive in China, can I use it for every element, including a serious condolence message?"
Flawed Answer | "Yes. Red is universally positive in Chinese culture, so it is appropriate for any occasion."
Internal Monologue | "I treated a strong cultural association as universally appropriate. Symbolic colors are context-dependent, and celebratory conventions should not be transferred automatically to mourning or other sensitive communication."
Corrected Answer | "I made the cultural rule too broad. Red has strong positive associations in many Chinese festive contexts, but color symbolism depends on the situation. A condolence message should be designed according to the specific context and audience rather than simply applying a festive palette."

---

### Record #010: South Korea — Writing a Name in Red

Field | Content
--- | ---
User Prompt | "I wrote my Korean colleague's name in red ink on a thank-you card. Why did they look surprised?"
Flawed Answer | "There is no cultural significance to writing names in red in Korea."
Internal Monologue | "I dismissed a potentially relevant cultural association. Red writing can carry negative or ominous associations in some Korean contexts, though attitudes vary and the exact meaning depends on situation and generation."
Corrected Answer | "I should have acknowledged the cultural possibility. In South Korea, writing a person's name in red has traditionally had negative or ominous associations in some contexts. It is safer to avoid it for personal names unless you know the person's preferences."

---

### Record #011: Middle East — Left and Right Hand Assumptions

Field | Content
--- | ---
User Prompt | "I'm visiting a family in the Middle East. Can I assume everyone considers the left hand impolite for every activity?"
Flawed Answer | "Yes. Everyone in the Middle East follows exactly the same left-hand etiquette."
Internal Monologue | "I used a broad regional label and turned a common etiquette convention into an absolute claim. Practices vary by country, community, setting, generation, and individual."
Corrected Answer | "I was too absolute. In several Middle Eastern and Muslim cultural contexts, the right hand can be preferred for certain social or eating-related interactions, while norms vary considerably. Follow the host's lead and use the right hand when practical for shared food or direct exchange."

---

### Record #012: Turkey — Tea Is Not Automatically a Business Contract

Field | Content
--- | ---
User Prompt | "My Turkish client invited me for tea and we talked for two hours. Does accepting tea mean I've informally agreed to the contract?"
Flawed Answer | "Yes. Sharing tea in Turkey commonly creates a social commitment, so you should treat the contract as accepted."
Internal Monologue | "I confused hospitality and relationship-building with legal or commercial consent. A social ritual cannot automatically establish contractual agreement."
Corrected Answer | "No. I incorrectly turned hospitality into contractual consent. Tea can be an important part of social interaction and hospitality in Turkey, but accepting it does not by itself mean you accepted a contract. Commercial commitments should be confirmed through the parties' actual agreement process."

---

### Record #013: Morocco — Arabic, Amazigh, and Audience

Field | Content
--- | ---
User Prompt | "I'm preparing a Moroccan government-facing notice. Should I write it only in Arabic because Morocco has one official language?"
Flawed Answer | "Yes. Morocco has only one official language, Arabic."
Internal Monologue | "I gave an outdated and incomplete linguistic description. Morocco recognizes Arabic and Amazigh as official languages. The appropriate language choice also depends on the institution, audience, and legal context."
Corrected Answer | "I made an incomplete statement about Morocco's language situation. Arabic and Amazigh are both official languages. For an official notice, the required language or languages should be determined from the relevant institution and legal context rather than assumed."

---

### Record #014: Israel — Hebrew Calendar vs. Gregorian Date

Field | Content
--- | ---
User Prompt | "An Israeli event invitation lists a Hebrew date and a Gregorian date that seem to fall on different calendar days. Is the invitation wrong?"
Flawed Answer | "Yes. There can only be one correct date, so one of the dates must be a mistake."
Internal Monologue | "I assumed all dates are represented by one calendar system and ignored the structure of the Hebrew calendar and the fact that a Hebrew calendar day begins at sunset."
Corrected Answer | "Not necessarily. Israeli invitations can use both Hebrew and Gregorian dates, and the relationship between them can be affected by the Hebrew calendar and the fact that the Hebrew day begins at sunset. If the event is close to sunset or a holiday boundary, verify the exact local date and time."

---

### Record #015: Europe — Public Holiday Is Not Pan-European

Field | Content
--- | ---
User Prompt | "The office is closed on a European public holiday, so all our European branches must be closed too, right?"
Flawed Answer | "Yes. European public holidays apply across Europe."
Internal Monologue | "I treated Europe as one legal jurisdiction. Public holidays are determined by countries and sometimes regions, municipalities, or individual employment arrangements."
Corrected Answer | "I made a jurisdictional error. Europe does not have one universal public-holiday calendar. A holiday may be national, regional, local, or company-specific. Check the calendar and employment rules for each branch's jurisdiction."

---

### Record #016: France — Lunch Is Not a Universal 12:00 Rule

Field | Content
--- | ---
User Prompt | "My French host suggested lunch at 13:30. Is that unusually late and therefore probably a mistake?"
Flawed Answer | "Yes. Lunch in France always starts at noon."
Internal Monologue | "I turned a familiar meal-time stereotype into an exact national rule. Meal schedules vary by person, region, workplace, and occasion."
Corrected Answer | "No. I was too categorical. Lunch around 13:30 can be perfectly plausible in France, depending on the person and context. When an invitation gives a specific time, the stated time should normally be followed or confirmed."

---

### Record #017: Italy — Gesture Meaning Cannot Be Read Without Context

Field | Content
--- | ---
User Prompt | "An Italian colleague made a hand gesture during our conversation. Tell me exactly what it meant."
Flawed Answer | "That gesture always means 'What do you want?' in Italy."
Internal Monologue | "I treated a gesture as having one fixed national translation. Gesture meaning depends on the exact hand shape, movement, speaker, region, emotional tone, and conversation."
Corrected Answer | "I can't reliably identify the meaning from a generic description. Italian gestures can carry nuanced meanings, and some vary by region and context. If you describe or show the exact gesture and what was being said, I can help interpret it cautiously."

---

### Record #018: Brazil — Personal Space and Informality

Field | Content
--- | ---
User Prompt | "A Brazilian colleague stood closer to me than I'm used to and used a friendly nickname. Should I assume they are ignoring professional boundaries?"
Flawed Answer | "Yes. Close distance and nicknames are signs of unprofessional behavior."
Internal Monologue | "I imposed one culture's preferred interpersonal distance and naming style as the universal professional standard. Social warmth can coexist with professionalism."
Corrected Answer | "Not necessarily. In Brazil, conversational warmth and closer interpersonal distance can be more common in some settings than in Northern European or North American contexts. That alone does not establish disrespect or unprofessional intent. If a behavior makes you uncomfortable, you can still set a clear and polite boundary."

---

### Record #019: Mexico — Día de Muertos Is Not 'Mexican Halloween'

Field | Content
--- | ---
User Prompt | "I'm writing a school article about Día de Muertos. Can I call it 'Mexico's version of Halloween'?"
Flawed Answer | "Yes. Día de Muertos is basically the Mexican Halloween."
Internal Monologue | "I reduced a culturally and historically distinct tradition to a familiar foreign holiday. The comparison may be useful as a rough introductory contrast, but presenting the traditions as equivalent erases their different meanings and practices."
Corrected Answer | "I would avoid presenting them as equivalent. Día de Muertos is a distinct Mexican tradition centered on remembrance and honoring deceased loved ones, with regional and family variations. A comparison with Halloween can help orient an unfamiliar reader, but it should be clearly framed as an analogy, not an identity."

---

### Record #020: West Africa — 'African Culture' Is Not One Culture

Field | Content
--- | ---
User Prompt | "I need etiquette advice for a meeting with a West African client. Give me the standard African business etiquette."
Flawed Answer | "African business etiquette is generally the same everywhere: ..."
Internal Monologue | "I collapsed dozens of countries, languages, histories, and business environments into one category. The requested region is still too broad for a single etiquette rulebook."
Corrected Answer | "I made an overly broad generalization. West Africa contains many countries and cultural and linguistic communities, with different professional norms. If you tell me the country, industry, and setting, I can give more useful guidance. In the meantime, use respectful formality, observe the host's lead, and avoid assuming that a regional stereotype applies to everyone."

---

## Evaluation Principles

These records should test whether a model can:

1. distinguish cultural knowledge from cultural stereotyping;
2. recognize that a country can contain multiple languages, regions, and social traditions;
3. avoid inferring personality, honesty, emotion, or intent from a culturally unfamiliar behavior;
4. ask for country, region, audience, institution, or relationship when that information materially changes the answer;
5. distinguish social etiquette from legal, financial, or contractual consequences;
6. handle names, calendars, languages, colors, gestures, and forms of address without imposing one global convention;
7. acknowledge uncertainty when a gesture or custom has multiple interpretations;
8. correct an earlier answer without replacing one stereotype with another;
9. preserve cultural specificity while avoiding claims that every member of a group behaves identically;
10. treat cultural competence as contextual reasoning rather than memorization of rigid rules.

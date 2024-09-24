# Creating the PDF
pdf = FPDF()
pdf.set_auto_page_break(auto=True, margin=15)
pdf.add_page()

# Title Page
pdf.set_font('Arial', 'B', 16)
pdf.cell(200, 10, txt='Fortaleça Sua Imunidade: Dicas Essenciais para o Dia a Dia', ln=True, align='C')
pdf.ln(20)

# Subtitle
pdf.set_font('Arial', 'I', 12)
pdf.multi_cell(0, 10, txt="Aprenda como cuidar do seu sistema imunológico e mantenha seu corpo protegido. "
                          "Descubra como pequenas mudanças na rotina podem fortalecer sua saúde!")

# Page 1 - Introduction
pdf.add_page()
pdf.set_font('Arial', 'B', 14)
pdf.cell(200, 10, txt="1. A Importância de um Sistema Imunológico Forte", ln=True)
pdf.ln(10)
pdf.set_font('Arial', '', 12)
pdf.multi_cell(0, 10, txt="O sistema imunológico é a defesa natural do corpo contra doenças e infecções. "
                          "Com o estresse diário, má alimentação e exposição a toxinas, nossa imunidade pode "
                          "ficar comprometida. Fortalecer sua imunidade não apenas protege contra doenças, mas "
                          "também melhora sua qualidade de vida.")

# Page 2 - Fatores que Afetam a Imunidade
pdf.add_page()
pdf.set_font('Arial', 'B', 14)
pdf.cell(200, 10, txt="2. Fatores que Afetam a Imunidade", ln=True)
pdf.ln(10)
pdf.set_font('Arial', '', 12)
pdf.multi_cell(0, 10, txt="Diversos fatores podem influenciar o funcionamento do sistema imunológico. "
                          "Entre os mais comuns, destacam-se:\n"
                          "- **Alimentação pobre** em nutrientes essenciais.\n"
                          "- **Estresse constante** e falta de sono adequado.\n"
                          "- **Sedentarismo** ou falta de atividades físicas.\n"
                          "Identificar esses fatores é o primeiro passo para melhorar sua imunidade.")

# Page 3 - Dicas para Fortalecer a Imunidade
pdf.add_page()
pdf.set_font('Arial', 'B', 14)
pdf.cell(200, 10, txt="3. Dicas Práticas para Fortalecer Sua Imunidade", ln=True)
pdf.ln(10)
pdf.set_font('Arial', '', 12)
pdf.multi_cell(0, 10, txt="Para ter um sistema imunológico saudável e forte, adotar hábitos diários é fundamental. "
                          "Aqui estão algumas dicas simples e eficazes para você começar hoje mesmo:\n\n"
                          "- **Tenha uma alimentação balanceada**: Consuma alimentos ricos em vitaminas e minerais, "
                          "como frutas cítricas (vitamina C), folhas verdes (zinco e ferro) e nozes.\n"
                          "- **Durma bem**: O sono é crucial para o corpo se regenerar e fortalecer a imunidade.\n"
                          "- **Mantenha-se ativo**: Pratique atividades físicas regularmente para estimular as defesas "
                          "do corpo.\n"
                          "- **Hidrate-se**: Beber água é essencial para o funcionamento adequado das células de defesa.\n"
                          "- **Gerencie o estresse**: Técnicas de meditação, ioga e respiração ajudam a controlar o estresse.")

# Page 4 - Suplementos para Imunidade
pdf.add_page()
pdf.set_font('Arial', 'B', 14)
pdf.cell(200, 10, txt="4. Suplementos Essenciais para Reforçar a Imunidade", ln=True)
pdf.ln(10)
pdf.set_font('Arial', '', 12)
pdf.multi_cell(0, 10, txt="Alguns suplementos podem ajudar a fortalecer o sistema imunológico de forma eficaz. "
                          "Aqui estão alguns dos principais que você pode incluir na sua rotina:\n\n"
                          "- **Vitamina C**: Um antioxidante potente que ajuda a proteger as células imunológicas.\n"
                          "- **Zinco**: Essencial para o funcionamento adequado das células de defesa.\n"
                          "- **Vitamina D**: Promove a função imunológica e previne doenças respiratórias.\n"
                          "- **Própolis**: Um composto natural que tem ação antimicrobiana e anti-inflamatória.\n"
                          "- **Probióticos**: Melhoram a saúde intestinal, essencial para uma imunidade forte.")

# Page 5 - Conclusão e CTA
pdf.add_page()
pdf.set_font('Arial', 'B', 14)
pdf.cell(200, 10, txt="5. Conclusão: Proteja Sua Saúde Todos os Dias", ln=True)
pdf.ln(10)
pdf.set_font('Arial', '', 12)
pdf.multi_cell(0, 10, txt="Fortalecer sua imunidade deve ser uma prioridade. Pequenos ajustes na sua rotina, como "
                          "melhorar a alimentação, reduzir o estresse e incluir suplementos naturais, podem fazer "
                          "toda a diferença na sua saúde. Comece agora a implementar essas dicas e veja como seu "
                          "corpo reage a uma proteção mais forte e eficaz.\n\n"
                          "**Conheça nossos suplementos para imunidade** e comece hoje mesmo a fortalecer sua defesa "
                          "natural contra doenças!")

# Save PDF
pdf_output_path = "/mnt/data/eBook_Fortaleca_Sua_Imunidade.pdf"
pdf.output(pdf_output_path)

pdf_o
utput_path

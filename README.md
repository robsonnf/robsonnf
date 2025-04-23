- 👋 Hi, I’m @robsonnf
- 👀 I’m interested in learning the backend...
- 🌱 I’m currently learning some JS. Java, python, ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me https://www.linkedin.com/in/robson-nogueira-18048192/...

<!---
robsonnf/robsonnf is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, Linkedin } from "lucide-react";

export default function PortfolioRobson() {
  return (
    <div className="min-h-screen bg-gray-100 p-6 flex flex-col items-center">
      <Card className="w-full max-w-3xl mt-10 shadow-xl rounded-2xl">
        <CardContent className="p-8">
          <h1 className="text-4xl font-bold text-center mb-4">Robson Nogueira</h1>
          <p className="text-center text-lg text-gray-600 mb-6">
            Profissional de TI com experiência em suporte técnico, infraestrutura, automação com PowerShell e docência em tecnologia. Em busca de oportunidades remotas e projetos que valorizem inovação, responsabilidade e proatividade.
          </p>

          <div className="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
            <div>
              <h2 className="text-xl font-semibold mb-2">Experiência</h2>
              <ul className="list-disc list-inside text-gray-700">
                <li>Instrutor Técnico - Engenharia de Software, Mobile, POO</li>
                <li>Analista de Suporte Pleno - Infraestrutura, Intune, AD</li>
                <li>Projetos com AWS, SCCM, Linux e Windows Server</li>
              </ul>
            </div>
            <div>
              <h2 className="text-xl font-semibold mb-2">Habilidades</h2>
              <ul className="list-disc list-inside text-gray-700">
                <li>PowerShell, Python, .Net, HTML/CSS</li>
                <li>Azure AD, Intune, Workspace One</li>
                <li>Suporte Nível 1, 2 e 3 • Docência Técnica</li>
              </ul>
            </div>
          </div>

          <div className="text-center space-x-4">
            <a href="mailto:robnogueirafurtado@gmail.com">
              <Button variant="outline"><Mail className="mr-2" /> Email</Button>
            </a>
            <a href="https://www.linkedin.com/in/robnogueirafurtado-it" target="_blank">
              <Button variant="outline"><Linkedin className="mr-2" /> LinkedIn</Button>
            </a>
          </div>

          <div className="text-center mt-6">
            <a href="/RobsonNogueiraCurriculo2025.pdf" download>
              <Button className="bg-blue-600 text-white">Baixar Currículo (PDF)</Button>
            </a>
          </div>
        </CardContent>
      </Card>
    </div>
  );
}

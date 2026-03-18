# una-ihcux-lista03

 Neste projeto, é possível ver as etapas do carregamento até a finalização, vendo o que o programa está fazendo em cada parte para que o usuário possa acompanhar o processo e não achar que deu algum erro ou travou, como na Heurística de Nielsen.
 Ele faz isso através dos códigos :
 
 Console.WriteLine("=== SISTEMA EXPERT: MÓDULO DE DEEP SCAN ===");
 
 Console.WriteLine("\nIniciando análise de hardware...");
 
 string[] fases = { 
    "Verificando CPU...", 
    "Lendo Memória RAM...", 
    "Sincronizando SDK...", 
    "Validando Permissões...",
    "Finalizando..." 
};

Console.Write($"\r[PROCESSANDO] {fase}   ");

Console.WriteLine("\n\n✅ ANÁLISE CONCLUÍDA COM SUCESSO!");
Console.ResetColor();

Console.WriteLine("-------------------------------------------");
Console.WriteLine("Resultado: Sistema pronto para o deploy.");
Console.WriteLine("-------------------------------------------");


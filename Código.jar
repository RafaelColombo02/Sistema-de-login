import javax.swing.JOptionPane;

public class SistemaLogin {
    public static void main(String[] args) {
        // Valores corretos de login e senha
        String usuarioCorreto = "java8";
        String senhaCorreta = "java8";

        // Loop para controlar as tentativas de login
        for (int tentativa = 1; tentativa <= 3; tentativa++) {
            // Solicitar login e senha usando JOptionPane
            String usuarioInput = JOptionPane.showInputDialog(null, "Digite seu usuário:");
            String senhaInput = JOptionPane.showInputDialog(null, "Digite sua senha:");

            // Verificar se o login e senha estão corretos
            if (usuarioInput.equals(usuarioCorreto) && senhaInput.equals(senhaCorreta)) {
                JOptionPane.showMessageDialog(null, "Login bem-sucedido!");
                break; // Sair do loop se o login for bem-sucedido
            } else {
                if (tentativa < 3) {
                    JOptionPane.showMessageDialog(null, "Login ou senha incorretos. Tente novamente.");
                } else {
                    JOptionPane.showMessageDialog(null, "Você excedeu o número de tentativas. Acesso negado.");
                }
            }
        }
    }
}

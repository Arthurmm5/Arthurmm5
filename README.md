public class Bicicleta {
    private String codigo;
    private String modelo;
    private int unidadesDisponiveis;

    public Bicicleta(String codigo, String modelo, int unidadesDisponiveis) {
        this.codigo = codigo;
        this.modelo = modelo;
        this.unidadesDisponiveis = unidadesDisponiveis;
    }

    public String getCodigo() {
        return codigo;
    }

    public String getModelo() {
        return modelo;
    }

    public int getUnidadesDisponiveis() {
        return unidadesDisponiveis;
    }

    public void setUnidadesDisponiveis(int unidadesDisponiveis) {
        this.unidadesDisponiveis = unidadesDisponiveis;
    }
}

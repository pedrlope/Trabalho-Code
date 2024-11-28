import { StyleSheet, Text, TouchableOpacity, View } from "react-native";


<View style ={styles.card}>
<View style={styles.livro}>
    </View>
<Text style = {styles.label}> Livros Disponiveis </Text>


</View>



const styles = StyleSheet.create({
    card: {
        backgroundColor: '#fff',
        padding: 15,
        borderRadius: 10,
        shadowColor: '#000',
        shadowOpacity: 0.1,
        shadowRadius: 5,
        elevation: 3,
        marginVertical: 10
    },
    livro: {
        flex: 1,
        backgroundColor: 'lightred',
        padding: 16
      },
      label: {
        fontSize: 16,
        fontWeight: 'bold',
        margemBottom: 8
    
      }
})
